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

Total: 456

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Acer          | TravelMate B118-M           | Notebook    | [68d9d26fe5](https://bsd-hardware.info/?probe=68d9d26fe5) | May 09, 2024 |
| Alienware     | Area-51m A00                | Notebook    | [53d5d4eb1e](https://bsd-hardware.info/?probe=53d5d4eb1e) | May 07, 2024 |
| Unknown       | X133                        | Notebook    | [524b7e6d8e](https://bsd-hardware.info/?probe=524b7e6d8e) | May 07, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [c9ad91fc61](https://bsd-hardware.info/?probe=c9ad91fc61) | May 07, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [79c4a2608c](https://bsd-hardware.info/?probe=79c4a2608c) | May 07, 2024 |
| Gigabyte      | P55-USB3                    | Desktop     | [9024f0074b](https://bsd-hardware.info/?probe=9024f0074b) | May 07, 2024 |
| Lenovo        | ThinkPad X240 20AMS3FY00    | Notebook    | [1dc74d60e6](https://bsd-hardware.info/?probe=1dc74d60e6) | May 06, 2024 |
| Dell          | Latitude 7390               | Notebook    | [b9b511f4d6](https://bsd-hardware.info/?probe=b9b511f4d6) | May 04, 2024 |
| MSI           | B360M BAZOOKA               | Desktop     | [d33325e752](https://bsd-hardware.info/?probe=d33325e752) | May 02, 2024 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [cda74e2f91](https://bsd-hardware.info/?probe=cda74e2f91) | May 02, 2024 |
| ASUSTek       | X202E                       | Notebook    | [0ed385a36d](https://bsd-hardware.info/?probe=0ed385a36d) | May 02, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [4878c18c8a](https://bsd-hardware.info/?probe=4878c18c8a) | May 01, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [26185f189e](https://bsd-hardware.info/?probe=26185f189e) | Apr 30, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [bb6303ed5b](https://bsd-hardware.info/?probe=bb6303ed5b) | Apr 29, 2024 |
| Lenovo        | ThinkPad X220 429135G       | Notebook    | [b681d0b406](https://bsd-hardware.info/?probe=b681d0b406) | Apr 23, 2024 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [150e135ba6](https://bsd-hardware.info/?probe=150e135ba6) | Apr 18, 2024 |
| Dell          | Latitude 7490               | Notebook    | [38f6023f20](https://bsd-hardware.info/?probe=38f6023f20) | Apr 14, 2024 |
| Dell          | Vostro 3350                 | Notebook    | [abe739e6c2](https://bsd-hardware.info/?probe=abe739e6c2) | Apr 13, 2024 |
| HP            | ProBook 645 G3              | Notebook    | [ea10ac1f83](https://bsd-hardware.info/?probe=ea10ac1f83) | Apr 12, 2024 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [15c55873cd](https://bsd-hardware.info/?probe=15c55873cd) | Apr 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a2cbe8253b](https://bsd-hardware.info/?probe=a2cbe8253b) | Apr 09, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3ccdd0084b](https://bsd-hardware.info/?probe=3ccdd0084b) | Apr 05, 2024 |
| Dell          | Latitude E5540              | Notebook    | [108e2acb98](https://bsd-hardware.info/?probe=108e2acb98) | Apr 01, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [56ea2c6719](https://bsd-hardware.info/?probe=56ea2c6719) | Apr 01, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [cfcf823cca](https://bsd-hardware.info/?probe=cfcf823cca) | Apr 01, 2024 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1010       | Desktop     | [4a359f1f86](https://bsd-hardware.info/?probe=4a359f1f86) | Apr 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| Lenovo        | 3743 NOK                    | Desktop     | [fd5dc51da2](https://bsd-hardware.info/?probe=fd5dc51da2) | Mar 31, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [f4dde6ddf5](https://bsd-hardware.info/?probe=f4dde6ddf5) | Mar 22, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [db1d3cd098](https://bsd-hardware.info/?probe=db1d3cd098) | Mar 19, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [403a4f0ea9](https://bsd-hardware.info/?probe=403a4f0ea9) | Mar 17, 2024 |
| Google        | Cave                        | Notebook    | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| ASUSTek       | H61M-K                      | Desktop     | [1f6840c3f3](https://bsd-hardware.info/?probe=1f6840c3f3) | Mar 12, 2024 |
| LG Electro... | R590-P.BE54P1               | Desktop     | [120ec3afe6](https://bsd-hardware.info/?probe=120ec3afe6) | Mar 09, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| HP            | Notebook                    | Notebook    | [15839305ee](https://bsd-hardware.info/?probe=15839305ee) | Mar 01, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [ac72a9a34a](https://bsd-hardware.info/?probe=ac72a9a34a) | Feb 23, 2024 |
| Dell          | Latitude E6540              | Notebook    | [92ba9b26e1](https://bsd-hardware.info/?probe=92ba9b26e1) | Feb 21, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [5392dc85bb](https://bsd-hardware.info/?probe=5392dc85bb) | Feb 21, 2024 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [39e4fb5eba](https://bsd-hardware.info/?probe=39e4fb5eba) | Feb 20, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [e933816d9f](https://bsd-hardware.info/?probe=e933816d9f) | Feb 19, 2024 |
| Biostar       | B450NH                      | Desktop     | [2db279db1d](https://bsd-hardware.info/?probe=2db279db1d) | Feb 16, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [fdeb2cee9d](https://bsd-hardware.info/?probe=fdeb2cee9d) | Feb 14, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [ca7e1f0fae](https://bsd-hardware.info/?probe=ca7e1f0fae) | Feb 12, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [a39d975ae9](https://bsd-hardware.info/?probe=a39d975ae9) | Feb 11, 2024 |
| Dell          | Latitude 7490               | Notebook    | [32828d5d84](https://bsd-hardware.info/?probe=32828d5d84) | Feb 10, 2024 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [37d30255bc](https://bsd-hardware.info/?probe=37d30255bc) | Feb 06, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [0e644c21cc](https://bsd-hardware.info/?probe=0e644c21cc) | Feb 02, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e747b9066e](https://bsd-hardware.info/?probe=e747b9066e) | Jan 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [7e24e6c0f2](https://bsd-hardware.info/?probe=7e24e6c0f2) | Jan 29, 2024 |
| Dell          | 0GDJXY A00                  | All in one  | [c7f489add0](https://bsd-hardware.info/?probe=c7f489add0) | Jan 28, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [c396fcc8d9](https://bsd-hardware.info/?probe=c396fcc8d9) | Jan 22, 2024 |
| MSI           | Z370-A PRO                  | Desktop     | [2b442ae151](https://bsd-hardware.info/?probe=2b442ae151) | Jan 20, 2024 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ebd5d3e03f](https://bsd-hardware.info/?probe=ebd5d3e03f) | Jan 19, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [d08f6339ae](https://bsd-hardware.info/?probe=d08f6339ae) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [2ab7b9d6b2](https://bsd-hardware.info/?probe=2ab7b9d6b2) | Jan 02, 2024 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [926ae04d23](https://bsd-hardware.info/?probe=926ae04d23) | Dec 31, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [fa4e90491b](https://bsd-hardware.info/?probe=fa4e90491b) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1c769a311c](https://bsd-hardware.info/?probe=1c769a311c) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [851f118bd5](https://bsd-hardware.info/?probe=851f118bd5) | Dec 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5281bb9e20](https://bsd-hardware.info/?probe=5281bb9e20) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d81a233601](https://bsd-hardware.info/?probe=d81a233601) | Dec 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0fe56565dc](https://bsd-hardware.info/?probe=0fe56565dc) | Dec 09, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [6ac792ecf6](https://bsd-hardware.info/?probe=6ac792ecf6) | Dec 05, 2023 |
| Dell          | Latitude E6330              | Notebook    | [7e0a01e9ad](https://bsd-hardware.info/?probe=7e0a01e9ad) | Dec 05, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Dell          | Latitude E5440              | Notebook    | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [19dfa9e36a](https://bsd-hardware.info/?probe=19dfa9e36a) | Nov 21, 2023 |
| Dell          | Precision 5520              | Notebook    | [45f5e399a4](https://bsd-hardware.info/?probe=45f5e399a4) | Nov 18, 2023 |
| HP            | Notebook                    | Notebook    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [b34836b090](https://bsd-hardware.info/?probe=b34836b090) | Nov 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0fd2711a56](https://bsd-hardware.info/?probe=0fd2711a56) | Nov 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d87ea88953](https://bsd-hardware.info/?probe=d87ea88953) | Nov 09, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [05bf5fb9f4](https://bsd-hardware.info/?probe=05bf5fb9f4) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Dell          | Latitude 5490               | Notebook    | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [dffb96790c](https://bsd-hardware.info/?probe=dffb96790c) | Oct 06, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [39fbf2c8dc](https://bsd-hardware.info/?probe=39fbf2c8dc) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [070c5dab4f](https://bsd-hardware.info/?probe=070c5dab4f) | Oct 02, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [6b58792f5e](https://bsd-hardware.info/?probe=6b58792f5e) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [6427b9defc](https://bsd-hardware.info/?probe=6427b9defc) | Oct 02, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b0aca42c84](https://bsd-hardware.info/?probe=b0aca42c84) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [68b8b9f531](https://bsd-hardware.info/?probe=68b8b9f531) | Sep 29, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| ASRock        | H670M-ITX/ax                | Desktop     | [1b6996f127](https://bsd-hardware.info/?probe=1b6996f127) | Sep 17, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | Notebook    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | Notebook    | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [26995b5321](https://bsd-hardware.info/?probe=26995b5321) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [af1a82a2d6](https://bsd-hardware.info/?probe=af1a82a2d6) | Aug 14, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [9d53e56e92](https://bsd-hardware.info/?probe=9d53e56e92) | Aug 13, 2023 |
| Samsung       | Q210                        | Notebook    | [2e25c6d2ec](https://bsd-hardware.info/?probe=2e25c6d2ec) | Aug 03, 2023 |
| Samsung       | Q210                        | Notebook    | [d3c5ab902d](https://bsd-hardware.info/?probe=d3c5ab902d) | Aug 03, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| Intel         | HM570                       | Desktop     | [4e0fd42418](https://bsd-hardware.info/?probe=4e0fd42418) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| Dell          | G3 3579                     | Notebook    | [8d9b29f231](https://bsd-hardware.info/?probe=8d9b29f231) | Jul 05, 2023 |
| Dell          | G3 3579                     | Notebook    | [f6fc15b1f4](https://bsd-hardware.info/?probe=f6fc15b1f4) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e212a51c70](https://bsd-hardware.info/?probe=e212a51c70) | Jul 03, 2023 |
| HP            | 15                          | Notebook    | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [cb769078b4](https://bsd-hardware.info/?probe=cb769078b4) | Jun 10, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [8bedc249ea](https://bsd-hardware.info/?probe=8bedc249ea) | Jun 10, 2023 |
| Dell          | Inspiron 7548               | Notebook    | [c80bb80e8f](https://bsd-hardware.info/?probe=c80bb80e8f) | Jun 10, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [fe5f99c4b0](https://bsd-hardware.info/?probe=fe5f99c4b0) | Jun 06, 2023 |
| Soyo          | SY-YL B550M                 | Desktop     | [1d1138e3c5](https://bsd-hardware.info/?probe=1d1138e3c5) | Jun 05, 2023 |
| Soyo          | SY-YL B550M                 | Desktop     | [79c6c2a177](https://bsd-hardware.info/?probe=79c6c2a177) | Jun 05, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [330c08c388](https://bsd-hardware.info/?probe=330c08c388) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [53cf3cea13](https://bsd-hardware.info/?probe=53cf3cea13) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [23cad3f06e](https://bsd-hardware.info/?probe=23cad3f06e) | May 28, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| Dell          | 0M9KCM A02                  | Desktop     | [932e96060f](https://bsd-hardware.info/?probe=932e96060f) | May 21, 2023 |
| HP            | ProBook 455 G3              | Notebook    | [b6a6c91115](https://bsd-hardware.info/?probe=b6a6c91115) | May 21, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0S300     | Notebook    | [44d30cfcf6](https://bsd-hardware.info/?probe=44d30cfcf6) | May 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dca662fc41](https://bsd-hardware.info/?probe=dca662fc41) | May 16, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [a3df9cd649](https://bsd-hardware.info/?probe=a3df9cd649) | May 14, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [262110252b](https://bsd-hardware.info/?probe=262110252b) | Apr 17, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [773b28fbc7](https://bsd-hardware.info/?probe=773b28fbc7) | Apr 16, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | Notebook    | [b960dc3bde](https://bsd-hardware.info/?probe=b960dc3bde) | Mar 25, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | Notebook    | [4cd1097c65](https://bsd-hardware.info/?probe=4cd1097c65) | Mar 24, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0K17763 WIN ... | Desktop     | [c9279ce424](https://bsd-hardware.info/?probe=c9279ce424) | Mar 13, 2023 |
| Star Labs     | StarBook                    | Notebook    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| MSI           | X299 PRO                    | Desktop     | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| Fujitsu       | FMVA532BSJ                  | Notebook    | [695e38d0ea](https://bsd-hardware.info/?probe=695e38d0ea) | Mar 10, 2023 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [37e1562772](https://bsd-hardware.info/?probe=37e1562772) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349S31       | Notebook    | [2b13f68cd6](https://bsd-hardware.info/?probe=2b13f68cd6) | Feb 28, 2023 |
| MSI           | X299 PRO                    | Desktop     | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [7d7fa2bbc9](https://bsd-hardware.info/?probe=7d7fa2bbc9) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | Notebook    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [9a0c17560f](https://bsd-hardware.info/?probe=9a0c17560f) | Feb 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [b42e3649a3](https://bsd-hardware.info/?probe=b42e3649a3) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a9928bd16e](https://bsd-hardware.info/?probe=a9928bd16e) | Feb 10, 2023 |
| HP            | 650                         | Notebook    | [48099613ec](https://bsd-hardware.info/?probe=48099613ec) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | Notebook    | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [fa42e2faf7](https://bsd-hardware.info/?probe=fa42e2faf7) | Jan 20, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| HP            | 18E7                        | Desktop     | [0b962b9400](https://bsd-hardware.info/?probe=0b962b9400) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| MSI           | X299 PRO                    | Desktop     | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
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


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GhostBSD 20.04.02 | 109       | 30.28%  |
| GhostBSD 21.08.27 | 40        | 11.11%  |
| GhostBSD 24.01.1  | 38        | 10.56%  |
| GhostBSD 23.10.1  | 28        | 7.78%   |
| GhostBSD 22.01.12 | 18        | 5%      |
| GhostBSD 23.06.01 | 15        | 4.17%   |
| GhostBSD 22.06.18 | 14        | 3.89%   |
| GhostBSD 23.02.02 | 10        | 2.78%   |
| GhostBSD 22.11.22 | 5         | 1.39%   |
| GhostBSD 23.07.13 | 4         | 1.11%   |
| GhostBSD 22.07.16 | 4         | 1.11%   |
| GhostBSD 22.06.26 | 4         | 1.11%   |
| GhostBSD 23.09.06 | 3         | 0.83%   |
| GhostBSD 23.07.29 | 3         | 0.83%   |
| GhostBSD 23.06.05 | 3         | 0.83%   |
| GhostBSD 23.04.23 | 3         | 0.83%   |
| GhostBSD 23.03.17 | 3         | 0.83%   |
| GhostBSD 22.11.02 | 3         | 0.83%   |
| GhostBSD 22.09.16 | 3         | 0.83%   |
| GhostBSD 22.08.23 | 3         | 0.83%   |
| GhostBSD 22.04.06 | 3         | 0.83%   |
| GhostBSD 23.09.29 | 2         | 0.56%   |
| GhostBSD 23.09.16 | 2         | 0.56%   |
| GhostBSD 23.07.20 | 2         | 0.56%   |
| GhostBSD 23.06.22 | 2         | 0.56%   |
| GhostBSD 23.05.22 | 2         | 0.56%   |
| GhostBSD 23.05.18 | 2         | 0.56%   |
| GhostBSD 22.08.06 | 2         | 0.56%   |
| GhostBSD 22.07.13 | 2         | 0.56%   |
| GhostBSD 22.04.22 | 2         | 0.56%   |
| GhostBSD 23.10.09 | 1         | 0.28%   |
| GhostBSD 23.07.04 | 1         | 0.28%   |
| GhostBSD 23.04.15 | 1         | 0.28%   |
| GhostBSD 23.04.02 | 1         | 0.28%   |
| GhostBSD 23.01.13 | 1         | 0.28%   |
| GhostBSD 22.12.20 | 1         | 0.28%   |
| GhostBSD 22.10.30 | 1         | 0.28%   |
| GhostBSD 22.10.12 | 1         | 0.28%   |
| GhostBSD 22.08.27 | 1         | 0.28%   |
| GhostBSD 22.07.31 | 1         | 0.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GhostBSD | 332       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 332       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| MATE             | 265       | 78.64%  |
| XFCE             | 44        | 13.06%  |
| KDE5             | 15        | 4.45%   |
| Cinnamon         | 3         | 0.89%   |
| Metacity (Marco) | 2         | 0.59%   |
| GNOME            | 2         | 0.59%   |
| openbox          | 1         | 0.3%    |
| LXQt             | 1         | 0.3%    |
| i3               | 1         | 0.3%    |
| helloDesktop     | 1         | 0.3%    |
| dwm              | 1         | 0.3%    |
| Console          | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 330       | 99.4%   |
| Wayland | 1         | 0.3%    |
| Console | 1         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 326       | 98.19%  |
| SDDM    | 4         | 1.2%    |
| Console | 2         | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 147       | 42.61%  |
| C       | 102       | 29.57%  |
| Unknown | 29        | 8.41%   |
| de_DE   | 21        | 6.09%   |
| es_ES   | 9         | 2.61%   |
| ru_RU   | 8         | 2.32%   |
| pt_BR   | 6         | 1.74%   |
| en_GB   | 5         | 1.45%   |
| pl_PL   | 3         | 0.87%   |
| it_IT   | 3         | 0.87%   |
| fr_FR   | 3         | 0.87%   |
| sk_SK   | 2         | 0.58%   |
| en_AU   | 2         | 0.58%   |
| zh_CN   | 1         | 0.29%   |
| UTF-8   | 1         | 0.29%   |
| sv_SE   | 1         | 0.29%   |
| en_NZ   | 1         | 0.29%   |
| el_GR   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 264       | 79.52%  |
| BIOS | 68        | 20.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 316       | 94.05%  |
| Ufs  | 20        | 5.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 322       | 96.99%  |
| MBR     | 9         | 2.71%   |
| Unknown | 1         | 0.3%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 70        | 21.08%  |
| Dell                                 | 62        | 18.67%  |
| ASUSTek Computer                     | 43        | 12.95%  |
| Hewlett-Packard                      | 29        | 8.73%   |
| MSI                                  | 19        | 5.72%   |
| Gigabyte Technology                  | 19        | 5.72%   |
| Acer                                 | 15        | 4.52%   |
| ASRock                               | 12        | 3.61%   |
| Apple                                | 10        | 3.01%   |
| Fujitsu                              | 6         | 1.81%   |
| Sony                                 | 4         | 1.2%    |
| Notebook                             | 4         | 1.2%    |
| Toshiba                              | 3         | 0.9%    |
| System76                             | 3         | 0.9%    |
| Samsung Electronics                  | 3         | 0.9%    |
| Alienware                            | 3         | 0.9%    |
| Unknown                              | 3         | 0.9%    |
| TUXEDO                               | 2         | 0.6%    |
| Star Labs                            | 2         | 0.6%    |
| Intel                                | 2         | 0.6%    |
| HUAWEI                               | 2         | 0.6%    |
| Huanan                               | 2         | 0.6%    |
| Supermicro                           | 1         | 0.3%    |
| Soyo                                 | 1         | 0.3%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.3%    |
| Quanta                               | 1         | 0.3%    |
| Panasonic                            | 1         | 0.3%    |
| MouseComputer                        | 1         | 0.3%    |
| Mini PC                              | 1         | 0.3%    |
| Medion                               | 1         | 0.3%    |
| LG Electronics                       | 1         | 0.3%    |
| Jumper                               | 1         | 0.3%    |
| GPU Company                          | 1         | 0.3%    |
| Google                               | 1         | 0.3%    |
| F-Plus Mobile                        | 1         | 0.3%    |
| Casper                               | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 4         | 1.2%    |
| Dell Latitude 7490                           | 3         | 0.9%    |
| Dell Inspiron 3542                           | 3         | 0.9%    |
| MSI MS-7B86                                  | 2         | 0.6%    |
| MSI MS-7817                                  | 2         | 0.6%    |
| MSI Modern 14 A10M                           | 2         | 0.6%    |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS           | 2         | 0.6%    |
| Lenovo ThinkPad T430s 2352CTO                | 2         | 0.6%    |
| HP Notebook                                  | 2         | 0.6%    |
| Dell XPS 13 9360                             | 2         | 0.6%    |
| Dell XPS 13 7390                             | 2         | 0.6%    |
| Dell Latitude E6540                          | 2         | 0.6%    |
| Dell Latitude E6420                          | 2         | 0.6%    |
| Dell Latitude E5440                          | 2         | 0.6%    |
| ASUS ZenBook UX325UA_UM325UA                 | 2         | 0.6%    |
| ASUS X202E                                   | 2         | 0.6%    |
| ASUS SABERTOOTH X58                          | 2         | 0.6%    |
| ASUS All Series                              | 2         | 0.6%    |
| TUXEDO InfinityBook13V3                      | 1         | 0.3%    |
| TUXEDO Aura 15 Gen1                          | 1         | 0.3%    |
| Toshiba Satellite L655                       | 1         | 0.3%    |
| Toshiba Satellite C855-1U4                   | 1         | 0.3%    |
| Toshiba Satellite C855                       | 1         | 0.3%    |
| System76 Lemur Pro                           | 1         | 0.3%    |
| System76 Kudu                                | 1         | 0.3%    |
| System76 Gazelle                             | 1         | 0.3%    |
| Supermicro X10DRi                            | 1         | 0.3%    |
| Star Labs StarBook                           | 1         | 0.3%    |
| Star Labs LabTop                             | 1         | 0.3%    |
| Soyo SY-YL B550M                             | 1         | 0.3%    |
| Sony VPCCB17FG                               | 1         | 0.3%    |
| Sony VGN-SZ3VWP_X                            | 1         | 0.3%    |
| Sony SVP1322M1EBI                            | 1         | 0.3%    |
| Sony SVP13225SCBI                            | 1         | 0.3%    |
| Shenzhen Meigao Electronic Equipment UM480XT | 1         | 0.3%    |
| Samsung Q210                                 | 1         | 0.3%    |
| Samsung 550P5C/550P7C                        | 1         | 0.3%    |
| Samsung 3570R/370R/470R/450R/510R/4450RV     | 1         | 0.3%    |
| Quanta 120-1333w                             | 1         | 0.3%    |
| Panasonic CF-19AHNC8FN                       | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 48        | 14.46%  |
| Dell Latitude           | 24        | 7.23%   |
| Dell Inspiron           | 16        | 4.82%   |
| Acer Aspire             | 10        | 3.01%   |
| Dell OptiPlex           | 7         | 2.11%   |
| ASUS PRIME              | 7         | 2.11%   |
| Lenovo IdeaPad          | 6         | 1.81%   |
| Dell XPS                | 6         | 1.81%   |
| Dell Precision          | 6         | 1.81%   |
| HP Laptop               | 5         | 1.51%   |
| HP EliteBook            | 5         | 1.51%   |
| ASUS ROG                | 5         | 1.51%   |
| Lenovo Yoga             | 4         | 1.2%    |
| ASUS TUF                | 4         | 1.2%    |
| Unknown                 | 4         | 1.2%    |
| Toshiba Satellite       | 3         | 0.9%    |
| Lenovo Legion           | 3         | 0.9%    |
| HP OMEN                 | 3         | 0.9%    |
| ASUS VivoBook           | 3         | 0.9%    |
| ASRock X570             | 3         | 0.9%    |
| Acer TravelMate         | 3         | 0.9%    |
| MSI MS-7B86             | 2         | 0.6%    |
| MSI MS-7817             | 2         | 0.6%    |
| MSI Modern              | 2         | 0.6%    |
| Lenovo ThinkCentre      | 2         | 0.6%    |
| HP ProBook              | 2         | 0.6%    |
| HP Pavilion             | 2         | 0.6%    |
| HP Notebook             | 2         | 0.6%    |
| HP 255                  | 2         | 0.6%    |
| Gigabyte GA-78LMT-USB3  | 2         | 0.6%    |
| Fujitsu LIFEBOOK        | 2         | 0.6%    |
| Fujitsu CELSIUS         | 2         | 0.6%    |
| ASUS ZenBook            | 2         | 0.6%    |
| ASUS X202E              | 2         | 0.6%    |
| ASUS SABERTOOTH         | 2         | 0.6%    |
| ASUS All                | 2         | 0.6%    |
| ASRock B450             | 2         | 0.6%    |
| Apple MacBookPro9       | 2         | 0.6%    |
| TUXEDO InfinityBook13V3 | 1         | 0.3%    |
| TUXEDO Aura             | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 43        | 12.95%  |
| 2018 | 35        | 10.54%  |
| 2013 | 29        | 8.73%   |
| 2021 | 28        | 8.43%   |
| 2019 | 25        | 7.53%   |
| 2014 | 23        | 6.93%   |
| 2022 | 22        | 6.63%   |
| 2012 | 20        | 6.02%   |
| 2011 | 20        | 6.02%   |
| 2016 | 19        | 5.72%   |
| 2015 | 19        | 5.72%   |
| 2023 | 12        | 3.61%   |
| 2017 | 12        | 3.61%   |
| 2009 | 9         | 2.71%   |
| 2008 | 9         | 2.71%   |
| 2010 | 6         | 1.81%   |
| 2007 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 212       | 63.86%  |
| Desktop     | 105       | 31.63%  |
| Convertible | 7         | 2.11%   |
| Mini pc     | 6         | 1.81%   |
| All in one  | 1         | 0.3%    |
| Server      | 1         | 0.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 329       | 99.1%   |
| Yes  | 3         | 0.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 134       | 40%     |
| 16.01-24.0      | 104       | 31.04%  |
| 4.01-8.0        | 48        | 14.33%  |
| 32.01-64.0      | 32        | 9.55%   |
| 64.01-256.0     | 8         | 2.39%   |
| 24.01-32.0      | 7         | 2.09%   |
| More than 256.0 | 1         | 0.3%    |
| 2.01-3.0        | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 138       | 40.83%  |
| 0.01-0.5   | 127       | 37.57%  |
| 1.01-2.0   | 46        | 13.61%  |
| 2.01-3.0   | 19        | 5.62%   |
| 3.01-4.0   | 4         | 1.18%   |
| 4.01-8.0   | 3         | 0.89%   |
| 24.01-32.0 | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 204       | 59.65%  |
| 2      | 77        | 22.51%  |
| 0      | 28        | 8.19%   |
| 3      | 11        | 3.22%   |
| 4      | 10        | 2.92%   |
| 5      | 6         | 1.75%   |
| 6      | 4         | 1.17%   |
| 22     | 1         | 0.29%   |
| 7      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 218       | 65.27%  |
| Yes       | 116       | 34.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 88.25%  |
| No        | 39        | 11.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 265       | 79.82%  |
| No        | 67        | 20.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 64.16%  |
| No        | 119       | 35.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 76        | 22.82%  |
| Germany      | 46        | 13.81%  |
| UK           | 17        | 5.11%   |
| France       | 16        | 4.8%    |
| Russia       | 15        | 4.5%    |
| Spain        | 11        | 3.3%    |
| Canada       | 11        | 3.3%    |
| Switzerland  | 8         | 2.4%    |
| Poland       | 8         | 2.4%    |
| Italy        | 7         | 2.1%    |
| Brazil       | 7         | 2.1%    |
| Taiwan       | 6         | 1.8%    |
| Japan        | 5         | 1.5%    |
| India        | 5         | 1.5%    |
| Bulgaria     | 5         | 1.5%    |
| Sweden       | 4         | 1.2%    |
| Norway       | 4         | 1.2%    |
| Netherlands  | 4         | 1.2%    |
| Malaysia     | 4         | 1.2%    |
| Indonesia    | 4         | 1.2%    |
| Denmark      | 4         | 1.2%    |
| Argentina    | 4         | 1.2%    |
| South Africa | 3         | 0.9%    |
| New Zealand  | 3         | 0.9%    |
| Finland      | 3         | 0.9%    |
| Czechia      | 3         | 0.9%    |
| China        | 3         | 0.9%    |
| Belgium      | 3         | 0.9%    |
| Australia    | 3         | 0.9%    |
| Ukraine      | 2         | 0.6%    |
| Turkey       | 2         | 0.6%    |
| Slovenia     | 2         | 0.6%    |
| Slovakia     | 2         | 0.6%    |
| Portugal     | 2         | 0.6%    |
| Philippines  | 2         | 0.6%    |
| Paraguay     | 2         | 0.6%    |
| Mauritius    | 2         | 0.6%    |
| Hungary      | 2         | 0.6%    |
| Hong Kong    | 2         | 0.6%    |
| El Salvador  | 2         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Bonn                        | 6         | 1.74%   |
| Bedburg                     | 6         | 1.74%   |
| Zurich                      | 5         | 1.45%   |
| Paris                       | 5         | 1.45%   |
| Taichung                    | 4         | 1.16%   |
| Sofia                       | 4         | 1.16%   |
| Madrid                      | 4         | 1.16%   |
| Indian Trail                | 4         | 1.16%   |
| Frederiksberg               | 4         | 1.16%   |
| Saratov                     | 3         | 0.87%   |
| Rome                        | 3         | 0.87%   |
| Oslo                        | 3         | 0.87%   |
| London                      | 3         | 0.87%   |
| Jakarta                     | 3         | 0.87%   |
| Franconville                | 3         | 0.87%   |
| Denver                      | 3         | 0.87%   |
| Chrusty                     | 3         | 0.87%   |
| Berlin                      | 3         | 0.87%   |
| Yokohama                    | 2         | 0.58%   |
| Winnipeg                    | 2         | 0.58%   |
| Whittier                    | 2         | 0.58%   |
| Wezeren                     | 2         | 0.58%   |
| Victoria                    | 2         | 0.58%   |
| Tucson                      | 2         | 0.58%   |
| Tomball                     | 2         | 0.58%   |
| Taipei                      | 2         | 0.58%   |
| Stiring-Wendel              | 2         | 0.58%   |
| St Petersburg               | 2         | 0.58%   |
| Skiatook                    | 2         | 0.58%   |
| San Salvador                | 2         | 0.58%   |
| San Nicolás de los Arroyos | 2         | 0.58%   |
| San Jose                    | 2         | 0.58%   |
| Salem                       | 2         | 0.58%   |
| Roslindale                  | 2         | 0.58%   |
| Richmond                    | 2         | 0.58%   |
| Port Elizabeth              | 2         | 0.58%   |
| Obninsk                     | 2         | 0.58%   |
| Nuremberg                   | 2         | 0.58%   |
| Milan                       | 2         | 0.58%   |
| Ludwigsburg                 | 2         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 94        | 123    | 20.94%  |
| WDC                 | 75        | 96     | 16.7%   |
| Seagate             | 46        | 61     | 10.24%  |
| Crucial             | 31        | 43     | 6.9%    |
| Kingston            | 28        | 29     | 6.24%   |
| Toshiba             | 26        | 33     | 5.79%   |
| SK hynix            | 15        | 19     | 3.34%   |
| SanDisk             | 15        | 20     | 3.34%   |
| Intel               | 15        | 15     | 3.34%   |
| Hitachi             | 15        | 15     | 3.34%   |
| A-DATA Technology   | 10        | 11     | 2.23%   |
| HGST                | 8         | 8      | 1.78%   |
| Micron Technology   | 7         | 7      | 1.56%   |
| Phison              | 6         | 8      | 1.34%   |
| PNY                 | 4         | 6      | 0.89%   |
| Transcend           | 3         | 3      | 0.67%   |
| Patriot             | 3         | 3      | 0.67%   |
| Gigabyte Technology | 3         | 3      | 0.67%   |
| China               | 3         | 3      | 0.67%   |
| Apple               | 3         | 3      | 0.67%   |
| Star Drive          | 2         | 2      | 0.45%   |
| SPCC                | 2         | 2      | 0.45%   |
| Plextor             | 2         | 2      | 0.45%   |
| OCZ                 | 2         | 2      | 0.45%   |
| Maxtor              | 2         | 2      | 0.45%   |
| KingSpec            | 2         | 2      | 0.45%   |
| GOODRAM             | 2         | 2      | 0.45%   |
| Fujitsu             | 2         | 2      | 0.45%   |
| XUM                 | 1         | 1      | 0.22%   |
| XrayDisk            | 1         | 1      | 0.22%   |
| XPG                 | 1         | 1      | 0.22%   |
| Vaseky              | 1         | 1      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| SSSTC               | 1         | 1      | 0.22%   |
| Silicon Motion      | 1         | 1      | 0.22%   |
| ShiJi               | 1         | 1      | 0.22%   |
| Netac               | 1         | 1      | 0.22%   |
| Neo Forza           | 1         | 2      | 0.22%   |
| LITEONIT            | 1         | 1      | 0.22%   |
| Lexar               | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB              | 7         | 1.43%   |
| Crucial CT1000MX500SSD1 1TB            | 7         | 1.43%   |
| WDC WDS500G2B0A-00SM50 500GB           | 6         | 1.23%   |
| Kingston SA400S37240G 240GB            | 6         | 1.23%   |
| Samsung SSD 860 QVO 1TB                | 5         | 1.02%   |
| Samsung SSD 850 EVO 500GB              | 5         | 1.02%   |
| Samsung SSD 870 EVO 500GB              | 4         | 0.82%   |
| Samsung SSD 860 EVO 500GB              | 4         | 0.82%   |
| Samsung SSD 860 EVO 1TB                | 4         | 0.82%   |
| Hitachi HTS541612J9SA00 120GB          | 4         | 0.82%   |
| Crucial CT240BX500SSD1 240GB           | 4         | 0.82%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 3         | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.61%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 3         | 0.61%   |
| Seagate ST500DM002-1BD142 500GB        | 3         | 0.61%   |
| Seagate ST1000LM049-2GH172 1TB         | 3         | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.61%   |
| Samsung SSD 970 EVO Plus 1TB           | 3         | 0.61%   |
| Kingston SA400S37120G 120GB            | 3         | 0.61%   |
| HGST HTS541010A9E680 1TB               | 3         | 0.61%   |
| WDC WDS480G2G0A-00JH30 480GB           | 2         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB           | 2         | 0.41%   |
| WDC WD40EFRX-68N32N0 4TB               | 2         | 0.41%   |
| WDC WD2000JS-55MHB0 192GB              | 2         | 0.41%   |
| WDC WD10EZEX-21M2NA0 1TB               | 2         | 0.41%   |
| Toshiba Q300 480GB                     | 2         | 0.41%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.41%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 2         | 0.41%   |
| Toshiba KBG40ZNT512G MEMORY 512GB      | 2         | 0.41%   |
| Toshiba HDWD120 2TB                    | 2         | 0.41%   |
| Toshiba DT01ACA050 500GB               | 2         | 0.41%   |
| Star Drive PCIe SSD 960GB              | 2         | 0.41%   |
| SK hynix SC311 SATA 512GB              | 2         | 0.41%   |
| SK hynix HFM512GD3JX013N 512GB         | 2         | 0.41%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.41%   |
| Seagate ST4000DM004-2CV104 4TB         | 2         | 0.41%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 2         | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB         | 2         | 0.41%   |
| Seagate ST1000VM002-1SD102 1TB         | 2         | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 49        | 62     | 34.51%  |
| Seagate             | 45        | 59     | 31.69%  |
| Hitachi             | 15        | 15     | 10.56%  |
| Toshiba             | 12        | 14     | 8.45%   |
| HGST                | 8         | 8      | 5.63%   |
| Samsung Electronics | 7         | 8      | 4.93%   |
| Maxtor              | 2         | 2      | 1.41%   |
| Fujitsu             | 2         | 2      | 1.41%   |
| HPT                 | 1         | 4      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 76     | 29.19%  |
| Crucial             | 26        | 33     | 12.44%  |
| Kingston            | 22        | 23     | 10.53%  |
| WDC                 | 16        | 19     | 7.66%   |
| SanDisk             | 15        | 20     | 7.18%   |
| SK hynix            | 7         | 7      | 3.35%   |
| Toshiba             | 6         | 8      | 2.87%   |
| Intel               | 6         | 6      | 2.87%   |
| A-DATA Technology   | 5         | 5      | 2.39%   |
| PNY                 | 4         | 6      | 1.91%   |
| Micron Technology   | 4         | 4      | 1.91%   |
| Transcend           | 3         | 3      | 1.44%   |
| Patriot             | 3         | 3      | 1.44%   |
| China               | 3         | 3      | 1.44%   |
| SPCC                | 2         | 2      | 0.96%   |
| Plextor             | 2         | 2      | 0.96%   |
| OCZ                 | 2         | 2      | 0.96%   |
| KingSpec            | 2         | 2      | 0.96%   |
| GOODRAM             | 2         | 2      | 0.96%   |
| Apple               | 2         | 2      | 0.96%   |
| XUM                 | 1         | 1      | 0.48%   |
| XrayDisk            | 1         | 1      | 0.48%   |
| Vaseky              | 1         | 1      | 0.48%   |
| Team                | 1         | 1      | 0.48%   |
| ShiJi               | 1         | 1      | 0.48%   |
| Seagate             | 1         | 1      | 0.48%   |
| Phison              | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| Neo Forza           | 1         | 2      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |
| Lexar               | 1         | 1      | 0.48%   |
| Hikvision           | 1         | 2      | 0.48%   |
| Fanxiang            | 1         | 1      | 0.48%   |
| Dell                | 1         | 2      | 0.48%   |
| Apacer              | 1         | 1      | 0.48%   |
| AMD                 | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 176       | 247    | 45.24%  |
| HDD  | 117       | 175    | 30.08%  |
| NVMe | 96        | 132    | 24.68%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 253       | 422    | 72.49%  |
| NVMe | 96        | 132    | 27.51%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 183       | 241    | 58.65%  |
| 0.51-1.0   | 84        | 120    | 26.92%  |
| 1.01-2.0   | 29        | 37     | 9.29%   |
| 3.01-4.0   | 11        | 13     | 3.53%   |
| 4.01-10.0  | 4         | 9      | 1.28%   |
| 10.01-20.0 | 1         | 2      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 98        | 28.24%  |
| 101-250        | 81        | 23.34%  |
| 251-500        | 64        | 18.44%  |
| 501-1000       | 36        | 10.37%  |
| 51-100         | 27        | 7.78%   |
| Unknown        | 20        | 5.76%   |
| 21-50          | 14        | 4.03%   |
| 1001-2000      | 6         | 1.73%   |
| More than 3000 | 1         | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 289       | 84.01%  |
| 21-50   | 28        | 8.14%   |
| Unknown | 20        | 5.81%   |
| 51-100  | 4         | 1.16%   |
| 101-250 | 2         | 0.58%   |
| 251-500 | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Hitachi HTS541612J9SA00 120GB                   | 4         | 4      | 6.56%   |
| Seagate ST500LT012-9WS142 500GB                 | 2         | 3      | 3.28%   |
| Seagate ST500DM002-1BD142 500GB                 | 2         | 2      | 3.28%   |
| Samsung Electronics SSD 870 EVO 500GB           | 2         | 2      | 3.28%   |
| Samsung Electronics HM320JI 320GB               | 2         | 2      | 3.28%   |
| Maxtor STM3320613AS 320GB                       | 2         | 2      | 3.28%   |
| Kingston SA400S37240G 240GB                     | 2         | 2      | 3.28%   |
| HGST HTS541010A9E680 1TB                        | 2         | 2      | 3.28%   |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 2      | 1.64%   |
| WDC WD800AAJS-00TDA0 80GB                       | 1         | 1      | 1.64%   |
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 1.64%   |
| WDC WD5000AAKS-60WWPA0 500GB                    | 1         | 1      | 1.64%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 1.64%   |
| WDC WD20EZRX-19D8PB0 2TB                        | 1         | 1      | 1.64%   |
| WDC WD10JPVX-60JC3T0 1TB                        | 1         | 1      | 1.64%   |
| WDC WD10EZEX-21M2NA0 1TB                        | 1         | 1      | 1.64%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB            | 1         | 1      | 1.64%   |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 1.64%   |
| Toshiba MK3263GSX 320GB                         | 1         | 1      | 1.64%   |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 1.64%   |
| SK hynix HFS256G39MND-2300A 256GB               | 1         | 1      | 1.64%   |
| ShiJi SSD 512GB                                 | 1         | 1      | 1.64%   |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 1.64%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 1.64%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 1.64%   |
| Seagate ST500DM002-1BC142 500GB                 | 1         | 1      | 1.64%   |
| Seagate ST4000DM004-2CV104 4TB                  | 1         | 1      | 1.64%   |
| Seagate ST3250310AS 250GB                       | 1         | 1      | 1.64%   |
| Seagate ST31500541AS 1.5TB                      | 1         | 1      | 1.64%   |
| Seagate ST2000DM008-2FR102 2TB                  | 1         | 1      | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 2      | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 980 500GB               | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 1.64%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 1.64%   |
| Samsung Electronics HD103SJ 1TB                 | 1         | 2      | 1.64%   |
| Patriot Inferno 60GB SSD                        | 1         | 1      | 1.64%   |
| OCZ AGILITY3 240GB                              | 1         | 1      | 1.64%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 1.64%   |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 16     | 21.67%  |
| Hitachi             | 9         | 9      | 15%     |
| WDC                 | 8         | 9      | 13.33%  |
| Samsung Electronics | 8         | 9      | 13.33%  |
| Toshiba             | 4         | 4      | 6.67%   |
| HGST                | 3         | 3      | 5%      |
| Crucial             | 3         | 3      | 5%      |
| Maxtor              | 2         | 2      | 3.33%   |
| Kingston            | 2         | 2      | 3.33%   |
| Intel               | 2         | 2      | 3.33%   |
| SK hynix            | 1         | 1      | 1.67%   |
| ShiJi               | 1         | 1      | 1.67%   |
| Patriot             | 1         | 1      | 1.67%   |
| OCZ                 | 1         | 1      | 1.67%   |
| Micron Technology   | 1         | 1      | 1.67%   |
| Fanxiang            | 1         | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 16     | 32.5%   |
| Hitachi             | 9         | 9      | 22.5%   |
| WDC                 | 7         | 7      | 17.5%   |
| Toshiba             | 3         | 3      | 7.5%    |
| Samsung Electronics | 3         | 4      | 7.5%    |
| HGST                | 3         | 3      | 7.5%    |
| Maxtor              | 2         | 2      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 44     | 64.91%  |
| SSD  | 19        | 20     | 33.33%  |
| NVMe | 1         | 1      | 1.75%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB         | 1         | 1      | 50%     |
| Intel SSDSCKKF512G8 SATA 512GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Intel   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 280       | 476    | 81.63%  |
| Malfunc  | 56        | 65     | 16.33%  |
| Detected | 5         | 11     | 1.46%   |
| Failed   | 2         | 2      | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 226       | 53.05%  |
| AMD                            | 64        | 15.02%  |
| Samsung Electronics            | 38        | 8.92%   |
| SanDisk                        | 17        | 3.99%   |
| Phison Electronics             | 11        | 2.58%   |
| SK hynix                       | 8         | 1.88%   |
| Kingston Technology Company    | 8         | 1.88%   |
| Nvidia                         | 7         | 1.64%   |
| Micron/Crucial Technology      | 7         | 1.64%   |
| ADATA Technology               | 6         | 1.41%   |
| ASMedia Technology             | 5         | 1.17%   |
| Toshiba                        | 4         | 0.94%   |
| Micron Technology              | 4         | 0.94%   |
| Silicon Motion                 | 3         | 0.7%    |
| Marvell Technology Group       | 3         | 0.7%    |
| JMicron Technology             | 3         | 0.7%    |
| MAXIO Technology (Hangzhou)    | 2         | 0.47%   |
| Solid State Storage Technology | 1         | 0.23%   |
| Shenzhen Longsys Electronics   | 1         | 0.23%   |
| Seagate Technology             | 1         | 0.23%   |
| OCZ Technology Group           | 1         | 0.23%   |
| KIOXIA                         | 1         | 0.23%   |
| Integrated Technology Express  | 1         | 0.23%   |
| HighPoint Technologies         | 1         | 0.23%   |
| Broadcom / LSI                 | 1         | 0.23%   |
| Biwin Storage Technology       | 1         | 0.23%   |
| Adaptec                        | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 47        | 10.15%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 27        | 5.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 22        | 4.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 21        | 4.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 3.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 3.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 2.16%   |
| Intel SATA Controller [RAID mode]                                                       | 9         | 1.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 1.94%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 8         | 1.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 1.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 6         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 1.3%    |
| Nvidia MCP79 AHCI Controller                                                            | 5         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 1.08%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5         | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.08%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5         | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5         | 1.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.86%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 4         | 0.86%   |
| Phison E12 NVMe Controller                                                              | 4         | 0.86%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4         | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 0.65%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 3         | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3         | 0.65%   |
| Intel SSD 660P Series                                                                   | 3         | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 252       | 60.72%  |
| NVMe | 107       | 25.78%  |
| RAID | 28        | 6.75%   |
| IDE  | 25        | 6.02%   |
| SCSI | 2         | 0.48%   |
| SAS  | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 250       | 75.3%   |
| AMD    | 82        | 24.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz      | 8         | 2.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 6         | 1.81%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz     | 5         | 1.51%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 5         | 1.51%   |
| Intel Core i5-5300U CPU @ 2.30GHz      | 5         | 1.51%   |
| Intel Core 2 Duo                       | 5         | 1.51%   |
| Intel Core i7-8650U CPU @ 1.90GHz      | 4         | 1.2%    |
| Intel Core i7-3520M CPU @ 2.90GHz      | 4         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz      | 4         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz      | 4         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz      | 3         | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz      | 3         | 0.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz      | 3         | 0.9%    |
| Intel Core i7-2620M CPU @ 2.70GHz      | 3         | 0.9%    |
| Intel Core i5-8350U CPU @ 1.70GHz      | 3         | 0.9%    |
| Intel Core i5-7300U CPU @ 2.60GHz      | 3         | 0.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz      | 3         | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz      | 3         | 0.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 3         | 0.9%    |
| Intel Core i3-3217U CPU @ 1.80GHz      | 3         | 0.9%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz   | 3         | 0.9%    |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz   | 3         | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics | 3         | 0.9%    |
| AMD Ryzen 7 5700U with Radeon Graphics | 3         | 0.9%    |
| AMD Ryzen 7 3700X 8-Core Processor     | 3         | 0.9%    |
| AMD Ryzen 7 2700X Eight-Core Processor | 3         | 0.9%    |
| AMD Ryzen 5 2600 Six-Core Processor    | 3         | 0.9%    |
| Intel CPU Version                      | 2         | 0.6%    |
| Intel Core i9-10980HK CPU @ 2.40GHz    | 2         | 0.6%    |
| Intel Core i7-8850H CPU @ 2.60GHz      | 2         | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz      | 2         | 0.6%    |
| Intel Core i7-6700K CPU @ 4.00GHz      | 2         | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz      | 2         | 0.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2         | 0.6%    |
| Intel Core i7-3740QM CPU @ 2.70GHz     | 2         | 0.6%    |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 2         | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz     | 2         | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz      | 2         | 0.6%    |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2         | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz      | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 94        | 28.31%  |
| Intel Core i7           | 74        | 22.29%  |
| AMD Ryzen 7             | 23        | 6.93%   |
| AMD Ryzen 5             | 23        | 6.93%   |
| Intel Core i3           | 17        | 5.12%   |
| Intel Core 2 Duo        | 14        | 4.22%   |
| Other                   | 13        | 3.92%   |
| Intel Xeon              | 10        | 3.01%   |
| Intel Celeron           | 9         | 2.71%   |
| Intel Pentium           | 7         | 2.11%   |
| AMD Ryzen 9             | 6         | 1.81%   |
| Intel Core i9           | 5         | 1.51%   |
| AMD Ryzen 3             | 5         | 1.51%   |
| AMD FX                  | 4         | 1.2%    |
| AMD A6                  | 4         | 1.2%    |
| Intel Core 2 Quad       | 2         | 0.6%    |
| AMD Ryzen 7 PRO         | 2         | 0.6%    |
| AMD Ryzen 3 PRO         | 2         | 0.6%    |
| AMD E1                  | 2         | 0.6%    |
| AMD Athlon              | 2         | 0.6%    |
| AMD A4                  | 2         | 0.6%    |
| AMD A10                 | 2         | 0.6%    |
| Intel Pentium Silver    | 1         | 0.3%    |
| Intel Pentium Dual-Core | 1         | 0.3%    |
| Intel Genuine           | 1         | 0.3%    |
| Intel Core m3           | 1         | 0.3%    |
| Intel Core 2            | 1         | 0.3%    |
| Intel Celeron Dual-Core | 1         | 0.3%    |
| AMD Ryzen Threadripper  | 1         | 0.3%    |
| AMD PRO A10             | 1         | 0.3%    |
| AMD E2                  | 1         | 0.3%    |
| AMD Athlon X4           | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 122       | 36.75%  |
| 4       | 105       | 31.63%  |
| 6       | 23        | 6.93%   |
| 16      | 22        | 6.63%   |
| 12      | 20        | 6.02%   |
| 8       | 20        | 6.02%   |
| Unknown | 11        | 3.31%   |
| 24      | 5         | 1.51%   |
| 32      | 2         | 0.6%    |
| 10      | 2         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 325       | 97.89%  |
| 2      | 7         | 2.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 188       | 56.63%  |
| 1       | 133       | 40.06%  |
| Unknown | 11        | 3.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 59        | 17.77%  |
| Haswell       | 34        | 10.24%  |
| IvyBridge     | 32        | 9.64%   |
| Skylake       | 26        | 7.83%   |
| SandyBridge   | 23        | 6.93%   |
| Penryn        | 19        | 5.72%   |
| Zen+          | 18        | 5.42%   |
| Zen 3         | 17        | 5.12%   |
| Zen 2         | 17        | 5.12%   |
| Unknown       | 15        | 4.52%   |
| Broadwell     | 12        | 3.61%   |
| Westmere      | 8         | 2.41%   |
| CometLake     | 7         | 2.11%   |
| Excavator     | 6         | 1.81%   |
| TigerLake     | 5         | 1.51%   |
| Piledriver    | 5         | 1.51%   |
| Nehalem       | 4         | 1.2%    |
| IceLake       | 4         | 1.2%    |
| Core          | 4         | 1.2%    |
| Zen           | 3         | 0.9%    |
| Silvermont    | 3         | 0.9%    |
| Puma          | 2         | 0.6%    |
| Goldmont plus | 2         | 0.6%    |
| Goldmont      | 2         | 0.6%    |
| K10 Llano     | 1         | 0.3%    |
| K10           | 1         | 0.3%    |
| Jaguar        | 1         | 0.3%    |
| Bulldozer     | 1         | 0.3%    |
| Bobcat        | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 196       | 50.78%  |
| Nvidia                     | 111       | 28.76%  |
| AMD                        | 77        | 19.95%  |
| Matrox Electronics Systems | 1         | 0.26%   |
| ASPEED Technology          | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 20        | 5.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 19        | 4.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 17        | 4.33%   |
| Intel UHD Graphics 620                                                      | 14        | 3.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 13        | 3.31%   |
| Intel HD Graphics 620                                                       | 11        | 2.8%    |
| Intel HD Graphics 5500                                                      | 11        | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 9         | 2.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9         | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 1.78%   |
| Intel HD Graphics 530                                                       | 7         | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 7         | 1.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 1.78%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 7         | 1.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 6         | 1.53%   |
| AMD Lucienne                                                                | 6         | 1.53%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5         | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                         | 5         | 1.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 1.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 1.02%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4         | 1.02%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4         | 1.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 1.02%   |
| Intel HD Graphics 630                                                       | 4         | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3         | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3         | 0.76%   |
| Nvidia C79 [GeForce 9400M]                                                  | 3         | 0.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 3         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 3         | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 3         | 0.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3         | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 3         | 0.76%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 2         | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 141       | 42.34%  |
| 1 x Nvidia      | 64        | 19.22%  |
| 1 x AMD         | 63        | 18.92%  |
| Intel + Nvidia  | 39        | 11.71%  |
| 2 x Intel       | 9         | 2.7%    |
| Intel + AMD     | 7         | 2.1%    |
| AMD + Nvidia    | 5         | 1.5%    |
| 2 x AMD         | 2         | 0.6%    |
| 2 x Nvidia      | 1         | 0.3%    |
| Nvidia + ASPEED | 1         | 0.3%    |
| 1 x Matrox      | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 274       | 82.04%  |
| Proprietary | 60        | 17.96%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 246       | 72.78%  |
| 1.01-2.0   | 24        | 7.1%    |
| 0.01-0.5   | 20        | 5.92%   |
| 0.51-1.0   | 16        | 4.73%   |
| 7.01-8.0   | 12        | 3.55%   |
| 3.01-4.0   | 12        | 3.55%   |
| 5.01-6.0   | 5         | 1.48%   |
| 8.01-16.0  | 2         | 0.59%   |
| 2.01-3.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 40        | 12.74%  |
| Samsung Electronics     | 38        | 12.1%   |
| Chimei Innolux          | 37        | 11.78%  |
| LG Display              | 34        | 10.83%  |
| BOE                     | 25        | 7.96%   |
| Dell                    | 17        | 5.41%   |
| Goldstar                | 12        | 3.82%   |
| BenQ                    | 11        | 3.5%    |
| Lenovo                  | 8         | 2.55%   |
| Philips                 | 7         | 2.23%   |
| Acer                    | 7         | 2.23%   |
| Hewlett-Packard         | 6         | 1.91%   |
| Ancor Communications    | 6         | 1.91%   |
| Apple                   | 5         | 1.59%   |
| Iiyama                  | 4         | 1.27%   |
| ViewSonic               | 3         | 0.96%   |
| Sharp                   | 3         | 0.96%   |
| LG Electronics          | 3         | 0.96%   |
| InfoVision              | 3         | 0.96%   |
| Fujitsu Siemens         | 3         | 0.96%   |
| CSO                     | 3         | 0.96%   |
| ASUSTek Computer        | 3         | 0.96%   |
| AOC                     | 3         | 0.96%   |
| Vizio                   | 2         | 0.64%   |
| PANDA                   | 2         | 0.64%   |
| Panasonic               | 2         | 0.64%   |
| Mi                      | 2         | 0.64%   |
| Idek Iiyama             | 2         | 0.64%   |
| HannStar                | 2         | 0.64%   |
| Chi Mei Optoelectronics | 2         | 0.64%   |
| ___                     | 1         | 0.32%   |
| WYT                     | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| Sony                    | 1         | 0.32%   |
| SANYO                   | 1         | 0.32%   |
| SAC                     | 1         | 0.32%   |
| Pixio                   | 1         | 0.32%   |
| Pioneer Electronic      | 1         | 0.32%   |
| OEM                     | 1         | 0.32%   |
| Lenovo Group Limited    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 3         | 0.94%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 3         | 0.94%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 3         | 0.94%   |
| Sharp LCD Monitor SHP1481 1920x1080 290x170mm 13.2-inch               | 2         | 0.63%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch  | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 0.63%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 0.63%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch           | 2         | 0.63%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 0.63%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 0.63%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 0.63%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 0.63%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                 | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 2         | 0.63%   |
| BOE LCD Monitor BOE08D5 1920x1080 340x190mm 15.3-inch                 | 2         | 0.63%   |
| BenQ EX3203R BNQ7F66 2560x1440 700x390mm 31.5-inch                    | 2         | 0.63%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO35EC 1366x768 340x190mm 15.3-inch         | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch         | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 0.63%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.31%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                  | 1         | 0.31%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                   | 1         | 0.31%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                   | 1         | 0.31%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch             | 1         | 0.31%   |
| ViewSonic VA1912w-3 VSC711C 1440x900 410x260mm 19.1-inch              | 1         | 0.31%   |
| ViewSonic LCD Monitor VA1938 Series                                   | 1         | 0.31%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                      | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 150       | 48.39%  |
| 1366x768 (WXGA)    | 64        | 20.65%  |
| 2560x1440 (QHD)    | 17        | 5.48%   |
| 1600x900 (HD+)     | 14        | 4.52%   |
| 3840x2160 (4K)     | 13        | 4.19%   |
| 1680x1050 (WSXGA+) | 8         | 2.58%   |
| 1280x800 (WXGA)    | 6         | 1.94%   |
| 1280x1024 (SXGA)   | 6         | 1.94%   |
| 1440x900 (WXGA+)   | 5         | 1.61%   |
| 2560x1080          | 4         | 1.29%   |
| Unknown            | 4         | 1.29%   |
| 2880x1800          | 3         | 0.97%   |
| 1360x768           | 3         | 0.97%   |
| 3840x1600          | 2         | 0.65%   |
| 2560x1600          | 2         | 0.65%   |
| 1920x1200 (WUXGA)  | 2         | 0.65%   |
| 9600x2160          | 1         | 0.32%   |
| 5120x1440          | 1         | 0.32%   |
| 4640x1080          | 1         | 0.32%   |
| 3440x1440          | 1         | 0.32%   |
| 3200x1080          | 1         | 0.32%   |
| 2806x900           | 1         | 0.32%   |
| 1920x540           | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 87        | 27.88%  |
| 13      | 56        | 17.95%  |
| 27      | 21        | 6.73%   |
| 21      | 21        | 6.73%   |
| 24      | 17        | 5.45%   |
| 23      | 17        | 5.45%   |
| Unknown | 17        | 5.45%   |
| 17      | 12        | 3.85%   |
| 19      | 11        | 3.53%   |
| 12      | 11        | 3.53%   |
| 31      | 7         | 2.24%   |
| 14      | 7         | 2.24%   |
| 11      | 7         | 2.24%   |
| 22      | 5         | 1.6%    |
| 34      | 3         | 0.96%   |
| 54      | 2         | 0.64%   |
| 40      | 2         | 0.64%   |
| 29      | 2         | 0.64%   |
| 16      | 2         | 0.64%   |
| 65      | 1         | 0.32%   |
| 60      | 1         | 0.32%   |
| 39      | 1         | 0.32%   |
| 37      | 1         | 0.32%   |
| 32      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 126       | 41.04%  |
| 501-600     | 50        | 16.29%  |
| 201-300     | 44        | 14.33%  |
| 401-500     | 33        | 10.75%  |
| Unknown     | 17        | 5.54%   |
| 351-400     | 14        | 4.56%   |
| 601-700     | 11        | 3.58%   |
| 801-900     | 4         | 1.3%    |
| 701-800     | 4         | 1.3%    |
| 1001-1500   | 4         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 240       | 81.91%  |
| 16/10   | 27        | 9.22%   |
| Unknown | 12        | 4.1%    |
| 5/4     | 5         | 1.71%   |
| 21/9    | 5         | 1.71%   |
| 3/2     | 2         | 0.68%   |
| 6/5     | 1         | 0.34%   |
| 32/9    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 69        | 22.19%  |
| 201-250        | 54        | 17.36%  |
| 81-90          | 46        | 14.79%  |
| 301-350        | 22        | 7.07%   |
| 71-80          | 17        | 5.47%   |
| 101-110        | 17        | 5.47%   |
| Unknown        | 17        | 5.47%   |
| 351-500        | 12        | 3.86%   |
| 151-200        | 12        | 3.86%   |
| 61-70          | 11        | 3.54%   |
| 121-130        | 10        | 3.22%   |
| 51-60          | 7         | 2.25%   |
| More than 1000 | 4         | 1.29%   |
| 251-300        | 4         | 1.29%   |
| 501-1000       | 4         | 1.29%   |
| 141-150        | 2         | 0.64%   |
| 111-120        | 2         | 0.64%   |
| 131-140        | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 100       | 32.36%  |
| 51-100        | 80        | 25.89%  |
| 101-120       | 78        | 25.24%  |
| 161-240       | 24        | 7.77%   |
| Unknown       | 17        | 5.5%    |
| More than 240 | 6         | 1.94%   |
| 1-50          | 4         | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 264       | 77.88%  |
| 0     | 41        | 12.09%  |
| 2     | 33        | 9.73%   |
| 3     | 1         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 202       | 40%     |
| Realtek Semiconductor                 | 146       | 28.91%  |
| Qualcomm Atheros                      | 55        | 10.89%  |
| Broadcom                              | 30        | 5.94%   |
| TP-Link                               | 11        | 2.18%   |
| Samsung Electronics                   | 6         | 1.19%   |
| Ralink Technology                     | 6         | 1.19%   |
| Nvidia                                | 5         | 0.99%   |
| Ericsson Business Mobile Networks     | 5         | 0.99%   |
| Sierra Wireless                       | 4         | 0.79%   |
| Edimax Technology                     | 4         | 0.79%   |
| Marvell Technology Group              | 3         | 0.59%   |
| ASUSTek Computer                      | 3         | 0.59%   |
| Ralink                                | 2         | 0.4%    |
| Qualcomm Atheros Communications       | 2         | 0.4%    |
| Qualcomm                              | 2         | 0.4%    |
| MediaTek                              | 2         | 0.4%    |
| Hewlett-Packard                       | 2         | 0.4%    |
| Generic                               | 2         | 0.4%    |
| Fibocom                               | 2         | 0.4%    |
| Aquantia                              | 2         | 0.4%    |
| Xiaomi                                | 1         | 0.2%    |
| Qualcomm Technologies                 | 1         | 0.2%    |
| OnePlus Technology (Shenzhen)         | 1         | 0.2%    |
| NetGear                               | 1         | 0.2%    |
| Microchip Technology                  | 1         | 0.2%    |
| Lenovo                                | 1         | 0.2%    |
| Huawei Technologies                   | 1         | 0.2%    |
| Dell                                  | 1         | 0.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 105       | 16.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 3.69%   |
| Intel Wi-Fi 6 AX200                                                    | 22        | 3.53%   |
| Intel Wireless 8265 / 8275                                             | 19        | 3.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 2.88%   |
| Intel Wireless 7265                                                    | 18        | 2.88%   |
| Intel I211 Gigabit Network Connection                                  | 13        | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                                  | 13        | 2.08%   |
| Intel Wireless 8260                                                    | 12        | 1.92%   |
| Intel Wireless 7260                                                    | 12        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 1.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 10        | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 1.28%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.28%   |
| Intel Wireless 3165                                                    | 7         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.96%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.8%    |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                         | 5         | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 4         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4         | 0.64%   |
| Ralink RT5370 Wireless Adapter                                         | 4         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.64%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 0.64%   |
| Intel Wireless 3160                                                    | 4         | 0.64%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 0.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 164       | 56.16%  |
| Qualcomm Atheros                      | 40        | 13.7%   |
| Realtek Semiconductor                 | 36        | 12.33%  |
| Broadcom                              | 16        | 5.48%   |
| TP-Link                               | 11        | 3.77%   |
| Ralink Technology                     | 6         | 2.05%   |
| Edimax Technology                     | 4         | 1.37%   |
| Sierra Wireless                       | 3         | 1.03%   |
| ASUSTek Computer                      | 3         | 1.03%   |
| Ralink                                | 2         | 0.68%   |
| Qualcomm Atheros Communications       | 2         | 0.68%   |
| MediaTek                              | 2         | 0.68%   |
| Qualcomm Technologies                 | 1         | 0.34%   |
| NetGear                               | 1         | 0.34%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 22        | 7.51%   |
| Intel Wireless 8265 / 8275                                     | 19        | 6.48%   |
| Intel Wireless 7265                                            | 18        | 6.14%   |
| Intel Wireless 8260                                            | 12        | 4.1%    |
| Intel Wireless 7260                                            | 12        | 4.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 3.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 3.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 2.73%   |
| Intel Wireless 3165                                            | 7         | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.71%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.37%   |
| Ralink RT5370 Wireless Adapter                                 | 4         | 1.37%   |
| Intel Wireless 3160                                            | 4         | 1.37%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.37%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 4         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 1.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 1.02%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3         | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.02%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.02%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 1.02%   |
| Sierra Wireless EM7455                                         | 2         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 132       | 42.44%  |
| Intel                         | 120       | 38.59%  |
| Qualcomm Atheros              | 19        | 6.11%   |
| Broadcom                      | 19        | 6.11%   |
| Samsung Electronics           | 6         | 1.93%   |
| Nvidia                        | 5         | 1.61%   |
| Marvell Technology Group      | 3         | 0.96%   |
| Qualcomm                      | 2         | 0.64%   |
| Aquantia                      | 2         | 0.64%   |
| Xiaomi                        | 1         | 0.32%   |
| OnePlus Technology (Shenzhen) | 1         | 0.32%   |
| Lenovo                        | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 105       | 33.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 23        | 7.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 18        | 5.73%   |
| Intel I211 Gigabit Network Connection                                          | 13        | 4.14%   |
| Intel Ethernet Connection (4) I219-LM                                          | 13        | 4.14%   |
| Intel Ethernet Connection I219-LM                                              | 8         | 2.55%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 6         | 1.91%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 1.91%   |
| Intel Ethernet Connection (2) I219-V                                           | 6         | 1.91%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 1.59%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 1.27%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 1.27%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 1.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.96%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 0.96%   |
| Intel Ethernet Controller I225-V                                               | 3         | 0.96%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.96%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.96%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 2         | 0.64%   |
| Qualcomm FP3                                                                   | 2         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.64%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 0.64%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 2         | 0.64%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.64%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.64%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.64%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2         | 0.64%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2         | 0.64%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.32%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.32%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 295       | 50.86%  |
| WiFi     | 268       | 46.21%  |
| Modem    | 9         | 1.55%   |
| Unknown  | 8         | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 217       | 56.81%  |
| WiFi     | 162       | 42.41%  |
| Modem    | 3         | 0.79%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 211       | 63.55%  |
| 1     | 110       | 33.13%  |
| 3     | 9         | 2.71%   |
| 5     | 1         | 0.3%    |
| 4     | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 330       | 99.1%   |
| Yes  | 3         | 0.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 128       | 60.09%  |
| Realtek Semiconductor           | 18        | 8.45%   |
| Qualcomm Atheros Communications | 11        | 5.16%   |
| Broadcom                        | 10        | 4.69%   |
| Apple                           | 10        | 4.69%   |
| Lite-On Technology              | 9         | 4.23%   |
| IMC Networks                    | 7         | 3.29%   |
| Dell                            | 6         | 2.82%   |
| ASUSTek Computer                | 3         | 1.41%   |
| Cambridge Silicon Radio         | 2         | 0.94%   |
| Alps Electric                   | 2         | 0.94%   |
| USI                             | 1         | 0.47%   |
| Toshiba                         | 1         | 0.47%   |
| Skylight Digital                | 1         | 0.47%   |
| Qcom                            | 1         | 0.47%   |
| MediaTek                        | 1         | 0.47%   |
| HTC (High Tech Computer)        | 1         | 0.47%   |
| Foxconn / Hon Hai               | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 66        | 30.99%  |
| Intel AX200 Bluetooth                                       | 20        | 9.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 15        | 7.04%   |
| Intel AX201 Bluetooth                                       | 12        | 5.63%   |
| Realtek Bluetooth Adapter                                   | 8         | 3.76%   |
| Apple Bluetooth Host Controller                             | 7         | 3.29%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 2.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 4         | 1.88%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 4         | 1.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 1.88%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.41%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 1.41%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 1.41%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 1.41%   |
| Intel AX210 Bluetooth                                       | 3         | 1.41%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 0.94%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 0.94%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 0.94%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 0.94%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 0.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 0.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 0.94%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 0.94%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.47%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 0.47%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 1         | 0.47%   |
| Realtek Wireless Bluetooth Adapter                          | 1         | 0.47%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.47%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.47%   |
| Qcom Broadcom Bluetooth USB                                 | 1         | 0.47%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 0.47%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 0.47%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.47%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.47%   |
| Intel AX211 Bluetooth                                       | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 239       | 53.47%  |
| AMD                   | 92        | 20.58%  |
| Nvidia                | 78        | 17.45%  |
| C-Media Electronics   | 7         | 1.57%   |
| Logitech              | 5         | 1.12%   |
| Lenovo                | 3         | 0.67%   |
| VIA Technologies      | 2         | 0.45%   |
| SteelSeries ApS       | 2         | 0.45%   |
| RODE Microphones      | 2         | 0.45%   |
| Creative Technology   | 2         | 0.45%   |
| Creative Labs         | 2         | 0.45%   |
| Corsair               | 2         | 0.45%   |
| Tenx Technology       | 1         | 0.22%   |
| Realtek Semiconductor | 1         | 0.22%   |
| Razer USA             | 1         | 0.22%   |
| Nam Tai E&E Products  | 1         | 0.22%   |
| Microsoft             | 1         | 0.22%   |
| JMTek                 | 1         | 0.22%   |
| GN Netcom             | 1         | 0.22%   |
| Focusrite-Novation    | 1         | 0.22%   |
| DSEA A/S              | 1         | 0.22%   |
| Cambridge Audio       | 1         | 0.22%   |
| Anlya.cn              | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 41        | 7.44%   |
| Intel Sunrise Point-LP HD Audio                                            | 39        | 7.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 5.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 24        | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 3.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 17        | 3.09%   |
| Intel 8 Series HD Audio Controller                                         | 17        | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 2.18%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 2.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 2.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 2.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 9         | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 1.63%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6         | 1.09%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.09%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.91%   |
| Nvidia MCP79 High Definition Audio                                         | 5         | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                              | 5         | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 0.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 0.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 0.91%   |
| Nvidia GM206 High Definition Audio Controller                              | 4         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.73%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.54%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 100       | 24.21%  |
| SK hynix                     | 88        | 21.31%  |
| Kingston                     | 43        | 10.41%  |
| Micron Technology            | 34        | 8.23%   |
| Crucial                      | 28        | 6.78%   |
| Unknown                      | 19        | 4.6%    |
| G.Skill                      | 18        | 4.36%   |
| Corsair                      | 17        | 4.12%   |
| Unknown                      | 11        | 2.66%   |
| Elpida                       | 8         | 1.94%   |
| A-DATA Technology            | 7         | 1.69%   |
| Ramaxel Technology           | 6         | 1.45%   |
| Team                         | 4         | 0.97%   |
| Nanya Technology             | 4         | 0.97%   |
| Transcend                    | 3         | 0.73%   |
| Unknown (ABCD)               | 2         | 0.48%   |
| GOODRAM                      | 2         | 0.48%   |
| Wodposit                     | 1         | 0.24%   |
| Undefined-00BA               | 1         | 0.24%   |
| Timetec                      | 1         | 0.24%   |
| Smart Modular                | 1         | 0.24%   |
| Smart                        | 1         | 0.24%   |
| Shenzhen Longsys             | 1         | 0.24%   |
| S                            | 1         | 0.24%   |
| Patriot Memory (PDP Systems) | 1         | 0.24%   |
| Patriot                      | 1         | 0.24%   |
| Neo Forza                    | 1         | 0.24%   |
| Kingmax                      | 1         | 0.24%   |
| Hewlett-Packard              | 1         | 0.24%   |
| GSkill                       | 1         | 0.24%   |
| GeIL                         | 1         | 0.24%   |
| CSX                          | 1         | 0.24%   |
| Avant                        | 1         | 0.24%   |
| Atermiter                    | 1         | 0.24%   |
| Apacer                       | 1         | 0.24%   |
| 09490000802C                 | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 11        | 2.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 2.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 7         | 1.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.4%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 5         | 1.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 5         | 1.17%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.93%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.93%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.93%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.7%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 3         | 0.7%    |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.47%   |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s                       | 2         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.47%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.47%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s          | 2         | 0.47%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.47%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.47%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 2         | 0.47%   |
| Samsung RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.47%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 158       | 46.88%  |
| DDR3    | 140       | 41.54%  |
| DDR2    | 10        | 2.97%   |
| Unknown | 9         | 2.67%   |
| LPDDR3  | 7         | 2.08%   |
| LPDDR4  | 6         | 1.78%   |
| SDRAM   | 2         | 0.59%   |
| DDR5    | 2         | 0.59%   |
| DDR     | 2         | 0.59%   |
| LPDDR5  | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 223       | 65.98%  |
| DIMM         | 98        | 28.99%  |
| Row Of Chips | 14        | 4.14%   |
| Chip         | 2         | 0.59%   |
| Unknown      | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 156       | 41.94%  |
| 4096  | 124       | 33.33%  |
| 16384 | 46        | 12.37%  |
| 2048  | 34        | 9.14%   |
| 32768 | 11        | 2.96%   |
| 1024  | 1         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 94        | 26.04%  |
| 3200    | 51        | 14.13%  |
| 2667    | 44        | 12.19%  |
| 2400    | 43        | 11.91%  |
| 1333    | 32        | 8.86%   |
| 2133    | 24        | 6.65%   |
| 1334    | 13        | 3.6%    |
| 800     | 9         | 2.49%   |
| 1867    | 8         | 2.22%   |
| 1067    | 7         | 1.94%   |
| 667     | 7         | 1.94%   |
| 2666    | 5         | 1.39%   |
| Unknown | 4         | 1.11%   |
| 1066    | 3         | 0.83%   |
| 4800    | 2         | 0.55%   |
| 4266    | 2         | 0.55%   |
| 3600    | 2         | 0.55%   |
| 3000    | 2         | 0.55%   |
| 6400    | 1         | 0.28%   |
| 4267    | 1         | 0.28%   |
| 3733    | 1         | 0.28%   |
| 3333    | 1         | 0.28%   |
| 3066    | 1         | 0.28%   |
| 2933    | 1         | 0.28%   |
| 1639    | 1         | 0.28%   |
| 1200    | 1         | 0.28%   |
| 975     | 1         | 0.28%   |

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


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| HP Laser 107a Printer | 1         | 50%     |
| Brother MFC-J485DW    | 1         | 50%     |

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
| Chicony Electronics                    | 51        | 27.57%  |
| Microdia                               | 25        | 13.51%  |
| Bison Electronics                      | 17        | 9.19%   |
| Realtek Semiconductor                  | 16        | 8.65%   |
| IMC Networks                           | 15        | 8.11%   |
| Sunplus Innovation Technology          | 11        | 5.95%   |
| Quanta                                 | 7         | 3.78%   |
| Logitech                               | 7         | 3.78%   |
| Suyin                                  | 6         | 3.24%   |
| Syntek                                 | 4         | 2.16%   |
| Luxvisions Innotech Limited            | 4         | 2.16%   |
| Alcor Micro                            | 4         | 2.16%   |
| Lite-On Technology                     | 3         | 1.62%   |
| Silicon Motion                         | 2         | 1.08%   |
| Ricoh                                  | 2         | 1.08%   |
| Apple                                  | 2         | 1.08%   |
| Xiongmai                               | 1         | 0.54%   |
| USB Camera                             | 1         | 0.54%   |
| Trust                                  | 1         | 0.54%   |
| OmniVision Technologies                | 1         | 0.54%   |
| Lenovo                                 | 1         | 0.54%   |
| Jiangxi Shinetech Optical              | 1         | 0.54%   |
| Intel                                  | 1         | 0.54%   |
| Importek                               | 1         | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 16        | 8.6%    |
| Bison Integrated Camera                              | 10        | 5.38%   |
| Microdia Integrated_Webcam_HD                        | 9         | 4.84%   |
| Microdia Integrated Webcam                           | 8         | 4.3%    |
| Sunplus Integrated_Webcam_HD                         | 7         | 3.76%   |
| IMC Networks Integrated Camera                       | 6         | 3.23%   |
| Realtek USB 2.0 PC Camera                            | 3         | 1.61%   |
| Realtek Integrated_Webcam_HD                         | 3         | 1.61%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 1.61%   |
| Logitech HD Pro Webcam C920                          | 3         | 1.61%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.61%   |
| Chicony Integrated Camera (1280x720@30)              | 3         | 1.61%   |
| Chicony HD WebCam                                    | 3         | 1.61%   |
| Suyin Integrated_Webcam_HD                           | 2         | 1.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 2         | 1.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 2         | 1.08%   |
| Realtek Lenovo EasyCamera                            | 2         | 1.08%   |
| Realtek Integrated Webcam HD                         | 2         | 1.08%   |
| Realtek Front Camera                                 | 2         | 1.08%   |
| Quanta VGA WebCam                                    | 2         | 1.08%   |
| Quanta HP TrueVision HD Camera                       | 2         | 1.08%   |
| Microdia Integrated Webcam HD                        | 2         | 1.08%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 1.08%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 1.08%   |
| Logitech HD Webcam C525                              | 2         | 1.08%   |
| IMC Networks USB 2.0 UVC HD Webcam                   | 2         | 1.08%   |
| IMC Networks Realtek PC Camera                       | 2         | 1.08%   |
| IMC Networks Realtek DMFT RGB                        | 2         | 1.08%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 1.08%   |
| Chicony Realtek DMFT RGB                             | 2         | 1.08%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 2         | 1.08%   |
| Chicony Integrated HP HD Webcam                      | 2         | 1.08%   |
| Chicony HP HD Camera                                 | 2         | 1.08%   |
| Chicony EasyCamera                                   | 2         | 1.08%   |
| Bison ThinkPad P50 Integrated Camera                 | 2         | 1.08%   |
| Bison ThinkPad Integrated Camera                     | 2         | 1.08%   |
| Apple FaceTime HD Camera                             | 2         | 1.08%   |
| Alcor Micro USB 2.0 Camera                           | 2         | 1.08%   |
| Xiongmai web camera                                  | 1         | 0.54%   |
| USB Camera USB Camera                                | 1         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 38.64%  |
| Synaptics                  | 9         | 20.45%  |
| Upek                       | 3         | 6.82%   |
| Shenzhen Goodix Technology | 3         | 6.82%   |
| Elan Microelectronics      | 3         | 6.82%   |
| STMicroelectronics         | 2         | 4.55%   |
| FocalTech Systems          | 2         | 4.55%   |
| Next Biometrics            | 1         | 2.27%   |
| LighTuning Technology      | 1         | 2.27%   |
| Fingerprint Cards          | 1         | 2.27%   |
| Broadcom                   | 1         | 2.27%   |
| AuthenTec                  | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 7         | 15.91%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 9.09%   |
| Validity Sensors Synaptics WBDI                                              | 3         | 6.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 6.82%   |
| Elan Fingerprint Sensor                                                      | 3         | 6.82%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 2         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 4.55%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 4.55%   |
| Synaptics WBDI                                                               | 2         | 4.55%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 4.55%   |
| FocalTech Systems Fingerprint Reader                                         | 2         | 4.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 2.27%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 2.27%   |
| Shenzhen Goodix  Fingerprint Device                                          | 1         | 2.27%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 2.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 2.27%   |
| Fingerprint Cards FPC Fingerprint Reader                                     | 1         | 2.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2.27%   |

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
| 1     | 113       | 32.85%  |
| 2     | 102       | 29.65%  |
| 3     | 50        | 14.53%  |
| 0     | 43        | 12.5%   |
| 4     | 26        | 7.56%   |
| 5     | 10        | 2.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 216       | 37.7%   |
| Bluetooth                | 138       | 24.08%  |
| Net/wireless             | 71        | 12.39%  |
| Card reader              | 50        | 8.73%   |
| Fingerprint reader       | 44        | 7.68%   |
| Firewire controller      | 24        | 4.19%   |
| Network                  | 14        | 2.44%   |
| Sound                    | 7         | 1.22%   |
| Storage                  | 5         | 0.87%   |
| Net/ethernet             | 3         | 0.52%   |
| Modem                    | 1         | 0.17%   |

