BSD in USA - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for BSD in USA.

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

Total: 555

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T460 20FMS0XL23    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Dell          | Latitude E7240              | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Deciso        | Netboard A20                | [0320675a86](https://bsd-hardware.info/?probe=0320675a86) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| Dell          | Latitude 5591               | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| Apple         | MacBook4,1                  | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Lenovo        | ThinkPad T420s 4174DL7      | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Latitude 5591               | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Dell          | Latitude 5591               | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Dell          | Latitude E6420              | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Lenovo        | ThinkPad X270 20HMS04P00    | [7647b7a0b2](https://bsd-hardware.info/?probe=7647b7a0b2) | Oct 07, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Dell          | Precision M4800             | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| Lenovo        | ThinkPad W530 2436CTO       | [6515a18552](https://bsd-hardware.info/?probe=6515a18552) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Deciso        | Netboard A20                | [388e27791d](https://bsd-hardware.info/?probe=388e27791d) | Sep 23, 2022 |
| Toshiba       | PORTEGE R700                | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Deciso        | Netboard A20                | [8af40be425](https://bsd-hardware.info/?probe=8af40be425) | Sep 13, 2022 |
| Dell          | XPS M1330                   | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Dell          | Precision 7540              | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| Dell          | Precision 7550              | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Valve         | Jupiter                     | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Dell          | Precision 7550              | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [296e81dd9d](https://bsd-hardware.info/?probe=296e81dd9d) | Aug 21, 2022 |
| Unknown       | Unknown                     | [1dfb3adb6b](https://bsd-hardware.info/?probe=1dfb3adb6b) | Aug 20, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b79fa4531e](https://bsd-hardware.info/?probe=b79fa4531e) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| Deciso        | NetBoard-A20                | [7ec18da9e4](https://bsd-hardware.info/?probe=7ec18da9e4) | Aug 19, 2022 |
| Google        | Peppy                       | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Dell          | Studio 1537                 | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| HP            | Victus by Gaming Laptop ... | [e09aa880f9](https://bsd-hardware.info/?probe=e09aa880f9) | Aug 16, 2022 |
| Deciso        | NetBoard-A10                | [9d82dae644](https://bsd-hardware.info/?probe=9d82dae644) | Aug 11, 2022 |
| Dell          | Inspiron 15-3567            | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Dell          | Inspiron 5559               | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Dell          | Precision 5560              | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Deciso        | Netboard A20                | [2bc988b18a](https://bsd-hardware.info/?probe=2bc988b18a) | Jul 18, 2022 |
| Dell          | Inspiron 15-3567            | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Deciso        | Netboard A20                | [a4be4171b6](https://bsd-hardware.info/?probe=a4be4171b6) | Jul 17, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Deciso        | Netboard A20                | [743b330db3](https://bsd-hardware.info/?probe=743b330db3) | Jul 12, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| Dell          | XPS 13 7390                 | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Unknown       | Unknown                     | [d9e6e5b83a](https://bsd-hardware.info/?probe=d9e6e5b83a) | Jun 29, 2022 |
| Deciso        | NetBoard-A10                | [ace8b06cd3](https://bsd-hardware.info/?probe=ace8b06cd3) | Jun 29, 2022 |
| Toshiba       | PORTEGE R700                | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [43d7380492](https://bsd-hardware.info/?probe=43d7380492) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [a3e3500ca5](https://bsd-hardware.info/?probe=a3e3500ca5) | Jun 15, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| GPD           | MicroPC                     | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| System76      | Galago Pro                  | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Dell          | Latitude E6430              | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| Deciso        | Netboard A20                | [eba0ffa870](https://bsd-hardware.info/?probe=eba0ffa870) | May 23, 2022 |
| Dell          | Precision M4800             | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Deciso        | Netboard A20                | [1fe95544bd](https://bsd-hardware.info/?probe=1fe95544bd) | May 22, 2022 |
| Timi          | TM1701                      | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| HP            | Pavilion dv6                | [73e328ad87](https://bsd-hardware.info/?probe=73e328ad87) | May 20, 2022 |
| Deciso        | Netboard A20                | [f78f6b9abb](https://bsd-hardware.info/?probe=f78f6b9abb) | May 20, 2022 |
| Dell          | Precision M4800             | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| Acer          | Aspire A715-42G             | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| Acer          | Aspire A715-42G             | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Dell          | Latitude 2100               | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| Dell          | Inspiron 15-7568            | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| Toshiba       | Satellite P25               | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Framework     | Laptop                      | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Apple         | MacBookPro8,3               | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| HP            | 2000                        | [e9599a9bc3](https://bsd-hardware.info/?probe=e9599a9bc3) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Lenovo        | G51-35 80M8                 | [285328cb61](https://bsd-hardware.info/?probe=285328cb61) | Apr 16, 2022 |
| Deciso        | Netboard A20                | [aa1f373bfb](https://bsd-hardware.info/?probe=aa1f373bfb) | Apr 12, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Deciso        | Netboard A20                | [d12cd9d1a1](https://bsd-hardware.info/?probe=d12cd9d1a1) | Apr 11, 2022 |
| Datto         | 1000                        | [745e356caa](https://bsd-hardware.info/?probe=745e356caa) | Apr 11, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [3b7da460a2](https://bsd-hardware.info/?probe=3b7da460a2) | Apr 10, 2022 |
| Lenovo        | ThinkPad T495 20NJ0000US    | [c626b32508](https://bsd-hardware.info/?probe=c626b32508) | Apr 09, 2022 |
| Dell          | Vostro 1400                 | [7e0964d31d](https://bsd-hardware.info/?probe=7e0964d31d) | Apr 08, 2022 |
| Deciso        | Netboard A20                | [c6217643cc](https://bsd-hardware.info/?probe=c6217643cc) | Apr 07, 2022 |
| Gigabyte      | MMLP7AP-00                  | [8116ea4eac](https://bsd-hardware.info/?probe=8116ea4eac) | Apr 07, 2022 |
| MSI           | Bravo 15 A4DDR              | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Datto         | 1000                        | [5974640141](https://bsd-hardware.info/?probe=5974640141) | Mar 31, 2022 |
| Deciso        | Netboard A20                | [51a8ceefee](https://bsd-hardware.info/?probe=51a8ceefee) | Mar 26, 2022 |
| Deciso        | Netboard A20                | [43a1f11ae0](https://bsd-hardware.info/?probe=43a1f11ae0) | Mar 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1af600b3ae](https://bsd-hardware.info/?probe=1af600b3ae) | Mar 24, 2022 |
| Lenovo        | ThinkPad X230 2325BV9       | [d2a16f6102](https://bsd-hardware.info/?probe=d2a16f6102) | Mar 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [693d365311](https://bsd-hardware.info/?probe=693d365311) | Mar 23, 2022 |
| Gateway       | NV55C                       | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| HP            | EliteBook 850 G3            | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| HP            | Pavilion dv6                | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [8bd2318fb6](https://bsd-hardware.info/?probe=8bd2318fb6) | Mar 15, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| Apple         | MacBookPro12,1              | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [2af47b6502](https://bsd-hardware.info/?probe=2af47b6502) | Mar 03, 2022 |
| Framework     | Laptop                      | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Dell          | Latitude D630               | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | EliteBook Folio 9470m       | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| Dell          | Inspiron 5559               | [c34e21ffd5](https://bsd-hardware.info/?probe=c34e21ffd5) | Feb 26, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Latitude 7480               | [f0e8e4a30a](https://bsd-hardware.info/?probe=f0e8e4a30a) | Feb 21, 2022 |
| Dell          | Inspiron 3537               | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [deac163b52](https://bsd-hardware.info/?probe=deac163b52) | Feb 19, 2022 |
| Acer          | AO725                       | [f53f627e62](https://bsd-hardware.info/?probe=f53f627e62) | Feb 19, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| ASUSTek       | 1215B                       | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| Notebook      | NS50_70MU                   | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Dell          | Latitude D630               | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | G3 3500                     | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| Deciso        | Netboard A20                | [43addbbe84](https://bsd-hardware.info/?probe=43addbbe84) | Jan 28, 2022 |
| Deciso        | Netboard A20                | [5f9588cc87](https://bsd-hardware.info/?probe=5f9588cc87) | Jan 27, 2022 |
| Apple         | MacBookPro9,2               | [208819a667](https://bsd-hardware.info/?probe=208819a667) | Jan 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [652e2e284f](https://bsd-hardware.info/?probe=652e2e284f) | Jan 26, 2022 |
| Dell          | Inspiron 5555               | [e54be582a7](https://bsd-hardware.info/?probe=e54be582a7) | Jan 25, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [bb6cc55d53](https://bsd-hardware.info/?probe=bb6cc55d53) | Jan 23, 2022 |
| Deciso        | Netboard A20                | [a25a10c535](https://bsd-hardware.info/?probe=a25a10c535) | Jan 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Deciso        | Netboard A20                | [3559282047](https://bsd-hardware.info/?probe=3559282047) | Jan 18, 2022 |
| Unknown       | Unknown                     | [699e8fdf32](https://bsd-hardware.info/?probe=699e8fdf32) | Jan 16, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| HP            | Laptop 15-dw2xxx            | [a6d7796cea](https://bsd-hardware.info/?probe=a6d7796cea) | Jan 13, 2022 |
| Dell          | Latitude 5510               | [a620d284cb](https://bsd-hardware.info/?probe=a620d284cb) | Jan 12, 2022 |
| Dell          | Latitude E5510              | [5c6b94df97](https://bsd-hardware.info/?probe=5c6b94df97) | Jan 09, 2022 |
| Dell          | Latitude E6530              | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell          | Inspiron 3505               | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| HP            | Laptop 14-dk0xxx            | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| Dell          | XPS 15 9575                 | [e7925aa387](https://bsd-hardware.info/?probe=e7925aa387) | Jan 05, 2022 |
| Framework     | Laptop                      | [324f0fdebc](https://bsd-hardware.info/?probe=324f0fdebc) | Jan 05, 2022 |
| Framework     | Laptop                      | [ba81f48282](https://bsd-hardware.info/?probe=ba81f48282) | Jan 05, 2022 |
| Framework     | Laptop                      | [9c201bb573](https://bsd-hardware.info/?probe=9c201bb573) | Jan 01, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [30590e8ccf](https://bsd-hardware.info/?probe=30590e8ccf) | Dec 31, 2021 |
| Dell          | Inspiron 3521               | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| HP            | 15 Notebook PC              | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [32080a81c5](https://bsd-hardware.info/?probe=32080a81c5) | Dec 15, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [e517ae0a82](https://bsd-hardware.info/?probe=e517ae0a82) | Dec 15, 2021 |
| Dell          | Inspiron 3521               | [d8bcea438a](https://bsd-hardware.info/?probe=d8bcea438a) | Dec 15, 2021 |
| Deciso        | Netboard A20                | [22eae64139](https://bsd-hardware.info/?probe=22eae64139) | Dec 14, 2021 |
| HP            | ZBook Studio G4             | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| Framework     | Laptop                      | [46dec0c088](https://bsd-hardware.info/?probe=46dec0c088) | Dec 08, 2021 |
| Framework     | Laptop                      | [a8cd4dc680](https://bsd-hardware.info/?probe=a8cd4dc680) | Dec 08, 2021 |
| Toshiba       | Satellite P755              | [44818070a2](https://bsd-hardware.info/?probe=44818070a2) | Dec 08, 2021 |
| Lenovo        | ThinkPad X61 7675H7U        | [545cbe065d](https://bsd-hardware.info/?probe=545cbe065d) | Dec 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4903f23b62](https://bsd-hardware.info/?probe=4903f23b62) | Dec 05, 2021 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [e4b923d500](https://bsd-hardware.info/?probe=e4b923d500) | Dec 02, 2021 |
| Lenovo        | ThinkPad T520 4243E51       | [82f5612822](https://bsd-hardware.info/?probe=82f5612822) | Nov 29, 2021 |
| Dell          | Latitude 5510               | [3da78c9445](https://bsd-hardware.info/?probe=3da78c9445) | Nov 24, 2021 |
| Acer          | Aspire A315-21              | [44c1f82bee](https://bsd-hardware.info/?probe=44c1f82bee) | Nov 20, 2021 |
| Deciso        | Netboard A20                | [6e7cf5b40b](https://bsd-hardware.info/?probe=6e7cf5b40b) | Nov 20, 2021 |
| Acer          | AO722                       | [98b88ae138](https://bsd-hardware.info/?probe=98b88ae138) | Nov 15, 2021 |
| Datto         | 1000                        | [294ee97676](https://bsd-hardware.info/?probe=294ee97676) | Nov 15, 2021 |
| Deciso        | Netboard A20                | [424007a067](https://bsd-hardware.info/?probe=424007a067) | Nov 13, 2021 |
| Deciso        | Netboard A20                | [127c951a65](https://bsd-hardware.info/?probe=127c951a65) | Nov 12, 2021 |
| Dell          | Vostro 1400                 | [1c594c9ded](https://bsd-hardware.info/?probe=1c594c9ded) | Nov 12, 2021 |
| Apple         | MacBook3,1                  | [61f1f0aef0](https://bsd-hardware.info/?probe=61f1f0aef0) | Nov 10, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [cdccf02902](https://bsd-hardware.info/?probe=cdccf02902) | Nov 04, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [2471e3f337](https://bsd-hardware.info/?probe=2471e3f337) | Nov 04, 2021 |
| Lenovo        | IdeaPad U430 Touch 20270    | [bf50a58600](https://bsd-hardware.info/?probe=bf50a58600) | Nov 04, 2021 |
| Dell          | Latitude D630               | [7e3a92badc](https://bsd-hardware.info/?probe=7e3a92badc) | Nov 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [d23636abb2](https://bsd-hardware.info/?probe=d23636abb2) | Oct 31, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [eb5c495379](https://bsd-hardware.info/?probe=eb5c495379) | Oct 30, 2021 |
| Acer          | Aspire E5-573G              | [e390271460](https://bsd-hardware.info/?probe=e390271460) | Oct 29, 2021 |
| HP            | Pavilion g6                 | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| GPD           | MicroPC                     | [8d0ac5e551](https://bsd-hardware.info/?probe=8d0ac5e551) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [2d72b6939d](https://bsd-hardware.info/?probe=2d72b6939d) | Oct 24, 2021 |
| Deciso        | Netboard A20                | [d0a79955c6](https://bsd-hardware.info/?probe=d0a79955c6) | Oct 22, 2021 |
| Deciso        | Netboard A20                | [36387cac1a](https://bsd-hardware.info/?probe=36387cac1a) | Oct 21, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 5570               | [9eab523504](https://bsd-hardware.info/?probe=9eab523504) | Oct 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |
| Apple         | MacBookPro10,1              | [1a3d253769](https://bsd-hardware.info/?probe=1a3d253769) | Oct 12, 2021 |
| Deciso        | Netboard A20                | [e4698339bc](https://bsd-hardware.info/?probe=e4698339bc) | Oct 10, 2021 |
| Deciso        | Netboard A20                | [bde99a9c6a](https://bsd-hardware.info/?probe=bde99a9c6a) | Oct 10, 2021 |
| ASUSTek       | K53E                        | [4572d8b5e7](https://bsd-hardware.info/?probe=4572d8b5e7) | Oct 08, 2021 |
| Framework     | Laptop                      | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| Dell          | Latitude E4300              | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [4b03ca3191](https://bsd-hardware.info/?probe=4b03ca3191) | Oct 03, 2021 |
| Dell          | Inspiron 3521               | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Valve         | Jupiter                     | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [efdfee9023](https://bsd-hardware.info/?probe=efdfee9023) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| HP            | Stream Notebook PC 11       | [c8ea8a4c4f](https://bsd-hardware.info/?probe=c8ea8a4c4f) | Sep 30, 2021 |
| HP            | Pavilion dm4                | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| Lenovo        | Flex 2-15 20405             | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| System76      | Darter Pro                  | [f99c9f56b7](https://bsd-hardware.info/?probe=f99c9f56b7) | Sep 25, 2021 |
| Lenovo        | ThinkPad T410 2518C5U       | [e937639adc](https://bsd-hardware.info/?probe=e937639adc) | Sep 25, 2021 |
| Dell          | Precision 7710              | [f0bebc2b21](https://bsd-hardware.info/?probe=f0bebc2b21) | Sep 23, 2021 |
| System76      | Galago Pro                  | [ebe0575f31](https://bsd-hardware.info/?probe=ebe0575f31) | Sep 23, 2021 |
| Dell          | Precision 7710              | [46e9438bf9](https://bsd-hardware.info/?probe=46e9438bf9) | Sep 22, 2021 |
| Dell          | Latitude 5491               | [006dc5a9f4](https://bsd-hardware.info/?probe=006dc5a9f4) | Sep 22, 2021 |
| Dell          | Latitude E7450              | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| Lenovo        | ThinkPad T61 64607EU        | [34e48b691d](https://bsd-hardware.info/?probe=34e48b691d) | Sep 17, 2021 |
| ASUSTek       | G551JW                      | [5624c69d4b](https://bsd-hardware.info/?probe=5624c69d4b) | Sep 16, 2021 |
| System76      | Galago Pro                  | [41cd62c0fe](https://bsd-hardware.info/?probe=41cd62c0fe) | Sep 16, 2021 |
| Lenovo        | ThinkPad W540 20BG0014US    | [b6dffe77eb](https://bsd-hardware.info/?probe=b6dffe77eb) | Sep 15, 2021 |
| HP            | G42                         | [738ccd1adf](https://bsd-hardware.info/?probe=738ccd1adf) | Sep 15, 2021 |
| Dell          | XPS 13 7390 2-in-1          | [577e0ed7fe](https://bsd-hardware.info/?probe=577e0ed7fe) | Sep 13, 2021 |
| HP            | 250 G5 Notebook PC          | [6e50039406](https://bsd-hardware.info/?probe=6e50039406) | Sep 09, 2021 |
| Apple         | MacBookPro6,2               | [4632683b4b](https://bsd-hardware.info/?probe=4632683b4b) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [4cc349d29a](https://bsd-hardware.info/?probe=4cc349d29a) | Sep 08, 2021 |
| Lenovo        | ThinkPad X250 20CM0046US    | [1ed50b75f1](https://bsd-hardware.info/?probe=1ed50b75f1) | Sep 08, 2021 |
| ASUSTek       | G551JW                      | [309b5d559f](https://bsd-hardware.info/?probe=309b5d559f) | Sep 07, 2021 |
| System76      | Galago Pro                  | [203560e1f5](https://bsd-hardware.info/?probe=203560e1f5) | Sep 07, 2021 |
| System76      | Galago Pro                  | [d3b33c7681](https://bsd-hardware.info/?probe=d3b33c7681) | Sep 07, 2021 |
| System76      | Kudu                        | [c10fc12e40](https://bsd-hardware.info/?probe=c10fc12e40) | Sep 05, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [713b72cfff](https://bsd-hardware.info/?probe=713b72cfff) | Sep 05, 2021 |
| HP            | 2000                        | [4e83c9da3f](https://bsd-hardware.info/?probe=4e83c9da3f) | Sep 02, 2021 |
| HP            | 2000                        | [7a48e639e6](https://bsd-hardware.info/?probe=7a48e639e6) | Sep 02, 2021 |
| Sony          | VGN-P698E                   | [c8274e858d](https://bsd-hardware.info/?probe=c8274e858d) | Aug 30, 2021 |
| Lenovo        | FLEX 3-1120 80LX            | [2f1a1a42b8](https://bsd-hardware.info/?probe=2f1a1a42b8) | Aug 29, 2021 |
| Lenovo        | ThinkPad P73 20QRS00200     | [dfc86a0368](https://bsd-hardware.info/?probe=dfc86a0368) | Aug 29, 2021 |
| HP            | ZBook 15 G3                 | [01521236eb](https://bsd-hardware.info/?probe=01521236eb) | Aug 27, 2021 |
| Apple         | MacBookPro8,3               | [455af20b0d](https://bsd-hardware.info/?probe=455af20b0d) | Aug 26, 2021 |
| HP            | ZBook 15 G3                 | [d05a95551d](https://bsd-hardware.info/?probe=d05a95551d) | Aug 24, 2021 |
| HP            | ZBook 15 G3                 | [c37c317da3](https://bsd-hardware.info/?probe=c37c317da3) | Aug 24, 2021 |
| Deciso        | Netboard A20                | [971ff9ea80](https://bsd-hardware.info/?probe=971ff9ea80) | Aug 22, 2021 |
| HP            | Pavilion dv6                | [8054d6310f](https://bsd-hardware.info/?probe=8054d6310f) | Aug 19, 2021 |
| IBM           | ThinkPad T42 2374K46        | [d93b6d68fa](https://bsd-hardware.info/?probe=d93b6d68fa) | Aug 18, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | [6f7976c329](https://bsd-hardware.info/?probe=6f7976c329) | Aug 16, 2021 |
| ASUSTek       | X55CR                       | [c7c812c2c9](https://bsd-hardware.info/?probe=c7c812c2c9) | Aug 15, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [b5018b8651](https://bsd-hardware.info/?probe=b5018b8651) | Aug 14, 2021 |
| Unknown       | Unknown                     | [3cf2ad31a8](https://bsd-hardware.info/?probe=3cf2ad31a8) | Aug 14, 2021 |
| HP            | Pavilion g6                 | [f1dc5150c2](https://bsd-hardware.info/?probe=f1dc5150c2) | Aug 13, 2021 |
| Dell          | Latitude E7240              | [762d8366d0](https://bsd-hardware.info/?probe=762d8366d0) | Aug 12, 2021 |
| Dell          | G3 3579                     | [91c803fdf2](https://bsd-hardware.info/?probe=91c803fdf2) | Aug 09, 2021 |
| HP            | 2000                        | [d2240a960b](https://bsd-hardware.info/?probe=d2240a960b) | Aug 05, 2021 |
| HP            | 2000                        | [65d183fe41](https://bsd-hardware.info/?probe=65d183fe41) | Aug 05, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [7364ae3b3d](https://bsd-hardware.info/?probe=7364ae3b3d) | Aug 04, 2021 |
| Apple         | MacBookPro8,1               | [1d941ee61d](https://bsd-hardware.info/?probe=1d941ee61d) | Jul 31, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [c3aa245b5d](https://bsd-hardware.info/?probe=c3aa245b5d) | Jul 27, 2021 |
| Unknown       | Unknown                     | [6f9c88c35e](https://bsd-hardware.info/?probe=6f9c88c35e) | Jul 24, 2021 |
| Dell          | G5 5505                     | [9933a09c4f](https://bsd-hardware.info/?probe=9933a09c4f) | Jul 24, 2021 |
| GPU Compan... | GWTN156-5                   | [bc44d767cc](https://bsd-hardware.info/?probe=bc44d767cc) | Jul 22, 2021 |
| Lenovo        | ThinkPad W520 42763KU       | [e16321d2fb](https://bsd-hardware.info/?probe=e16321d2fb) | Jul 21, 2021 |
| IBM           | ThinkPad T43 26686CU        | [122a5774ab](https://bsd-hardware.info/?probe=122a5774ab) | Jul 21, 2021 |
| IBM           | ThinkPad T43 26686CU        | [fdb4ebcf10](https://bsd-hardware.info/?probe=fdb4ebcf10) | Jul 21, 2021 |
| Apple         | MacBookPro8,1               | [89a9db74f9](https://bsd-hardware.info/?probe=89a9db74f9) | Jul 21, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [04b19bd02a](https://bsd-hardware.info/?probe=04b19bd02a) | Jul 21, 2021 |
| HP            | Stream 11 Pro G4 EE         | [bd2bf6b0a0](https://bsd-hardware.info/?probe=bd2bf6b0a0) | Jul 20, 2021 |
| Dell          | Inspiron 3521               | [1fed4e841b](https://bsd-hardware.info/?probe=1fed4e841b) | Jul 19, 2021 |
| Dell          | Inspiron 5559               | [e38b3f1f93](https://bsd-hardware.info/?probe=e38b3f1f93) | Jul 19, 2021 |
| Framework     | Laptop                      | [8a7b477512](https://bsd-hardware.info/?probe=8a7b477512) | Jul 15, 2021 |
| Apple         | MacBookPro9,2               | [6cca4dee6f](https://bsd-hardware.info/?probe=6cca4dee6f) | Jul 15, 2021 |
| Framework     | Laptop                      | [647138144b](https://bsd-hardware.info/?probe=647138144b) | Jul 14, 2021 |
| Apple         | MacBook5,1                  | [1e54d2fbdf](https://bsd-hardware.info/?probe=1e54d2fbdf) | Jul 05, 2021 |
| Apple         | MacBook5,1                  | [f5d7a16498](https://bsd-hardware.info/?probe=f5d7a16498) | Jul 05, 2021 |
| Unknown       | Unknown                     | [fb7b81afdd](https://bsd-hardware.info/?probe=fb7b81afdd) | Jul 04, 2021 |
| HP            | Pavilion dm1                | [a863347147](https://bsd-hardware.info/?probe=a863347147) | Jul 03, 2021 |
| HP            | ProBook 4440s               | [4aac49bc1e](https://bsd-hardware.info/?probe=4aac49bc1e) | Jul 01, 2021 |
| Dell          | Inspiron 15-5568            | [3ed52ae70d](https://bsd-hardware.info/?probe=3ed52ae70d) | Jul 01, 2021 |
| HP            | Pavilion 17                 | [9929e0c39b](https://bsd-hardware.info/?probe=9929e0c39b) | Jun 30, 2021 |
| Toshiba       | Satellite C655D             | [10bdf263b3](https://bsd-hardware.info/?probe=10bdf263b3) | Jun 27, 2021 |
| Unknown       | Unknown                     | [dcfbb8a46e](https://bsd-hardware.info/?probe=dcfbb8a46e) | Jun 26, 2021 |
| Dell          | Latitude E6420              | [2e8b431cc6](https://bsd-hardware.info/?probe=2e8b431cc6) | Jun 25, 2021 |
| Lenovo        | ThinkPad W520 42763KU       | [591cbc0879](https://bsd-hardware.info/?probe=591cbc0879) | Jun 24, 2021 |
| Dell          | Inspiron 5567               | [0b90603ace](https://bsd-hardware.info/?probe=0b90603ace) | Jun 23, 2021 |
| Dell          | Precision 7710              | [33653d0c28](https://bsd-hardware.info/?probe=33653d0c28) | Jun 22, 2021 |
| Lenovo        | ThinkPad X230 2325WWB       | [786669cc9c](https://bsd-hardware.info/?probe=786669cc9c) | Jun 21, 2021 |
| Dell          | Studio 1558                 | [c2ba752ab5](https://bsd-hardware.info/?probe=c2ba752ab5) | Jun 20, 2021 |
| Unknown       | Unknown                     | [f37bf77853](https://bsd-hardware.info/?probe=f37bf77853) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [8c78180ff9](https://bsd-hardware.info/?probe=8c78180ff9) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [2e7a8b5be3](https://bsd-hardware.info/?probe=2e7a8b5be3) | Jun 20, 2021 |
| IBM           | ThinkPad T42 2374K46        | [acf931a3e0](https://bsd-hardware.info/?probe=acf931a3e0) | Jun 19, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [7138c789e3](https://bsd-hardware.info/?probe=7138c789e3) | Jun 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [0fe1337b93](https://bsd-hardware.info/?probe=0fe1337b93) | Jun 19, 2021 |
| Dell          | Latitude E5420              | [1ed3ff35f6](https://bsd-hardware.info/?probe=1ed3ff35f6) | Jun 19, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [7d36d27958](https://bsd-hardware.info/?probe=7d36d27958) | Jun 19, 2021 |
| Lenovo        | ThinkPad Edge E530 62724... | [78abd376db](https://bsd-hardware.info/?probe=78abd376db) | Jun 18, 2021 |
| Lenovo        | ThinkPad T420 4236FJ1       | [808f58228e](https://bsd-hardware.info/?probe=808f58228e) | Jun 17, 2021 |
| Dell          | G5 5505                     | [97319295ee](https://bsd-hardware.info/?probe=97319295ee) | Jun 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [1138d47591](https://bsd-hardware.info/?probe=1138d47591) | Jun 10, 2021 |
| Dell          | Latitude D530               | [ef0dac3de0](https://bsd-hardware.info/?probe=ef0dac3de0) | Jun 09, 2021 |
| Acer          | Aspire E5-573G              | [52de90ff3d](https://bsd-hardware.info/?probe=52de90ff3d) | Jun 02, 2021 |
| Apple         | MacBookPro9,1               | [afc70d9c77](https://bsd-hardware.info/?probe=afc70d9c77) | Jun 01, 2021 |
| Lenovo        | ThinkPad T490 20N3X50500    | [6311d603ff](https://bsd-hardware.info/?probe=6311d603ff) | May 31, 2021 |
| System76      | Gazelle                     | [f9c37f2c8d](https://bsd-hardware.info/?probe=f9c37f2c8d) | May 30, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [9dd5a9eeef](https://bsd-hardware.info/?probe=9dd5a9eeef) | May 30, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [107ac19795](https://bsd-hardware.info/?probe=107ac19795) | May 28, 2021 |
| Acer          | Nitro AN515-54              | [337a8b5a3d](https://bsd-hardware.info/?probe=337a8b5a3d) | May 28, 2021 |
| ASUSTek       | 1015PX                      | [c6e717c1e9](https://bsd-hardware.info/?probe=c6e717c1e9) | May 24, 2021 |
| Unknown       | Unknown                     | [b296fb35e2](https://bsd-hardware.info/?probe=b296fb35e2) | May 19, 2021 |
| Unknown       | Unknown                     | [750e01de05](https://bsd-hardware.info/?probe=750e01de05) | May 19, 2021 |
| ASUSTek       | G750JM                      | [37be4ea27a](https://bsd-hardware.info/?probe=37be4ea27a) | May 13, 2021 |
| Apple         | MacBookPro6,2               | [0ab44e95df](https://bsd-hardware.info/?probe=0ab44e95df) | May 12, 2021 |
| Dell          | G5 5505                     | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Dell          | G5 5505                     | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| Dell          | Latitude E5570              | [c8477da717](https://bsd-hardware.info/?probe=c8477da717) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | [10af242f8b](https://bsd-hardware.info/?probe=10af242f8b) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | [b0b4ca9f27](https://bsd-hardware.info/?probe=b0b4ca9f27) | May 07, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [d5adf152a7](https://bsd-hardware.info/?probe=d5adf152a7) | May 05, 2021 |
| HP            | Laptop 17-by0xxx            | [47221a4d1d](https://bsd-hardware.info/?probe=47221a4d1d) | Apr 30, 2021 |
| Toshiba       | Satellite C655D             | [6398601e16](https://bsd-hardware.info/?probe=6398601e16) | Apr 29, 2021 |
| Dell          | Inspiron N4010              | [c1a55b1147](https://bsd-hardware.info/?probe=c1a55b1147) | Apr 29, 2021 |
| Lenovo        | ThinkPad T430 2344C4U       | [0f001f65d2](https://bsd-hardware.info/?probe=0f001f65d2) | Apr 27, 2021 |
| Dell          | Latitude E5420              | [32f03aa888](https://bsd-hardware.info/?probe=32f03aa888) | Apr 27, 2021 |
| Dell          | Latitude E5420              | [4b4cd45ac7](https://bsd-hardware.info/?probe=4b4cd45ac7) | Apr 26, 2021 |
| Dell          | Latitude E5420              | [6457b99e73](https://bsd-hardware.info/?probe=6457b99e73) | Apr 26, 2021 |
| Dell          | Precision 5510              | [063d746a48](https://bsd-hardware.info/?probe=063d746a48) | Apr 25, 2021 |
| Dell          | Precision 5510              | [6bb3b7aa11](https://bsd-hardware.info/?probe=6bb3b7aa11) | Apr 25, 2021 |
| HP            | ProBook 4530s               | [4fb8582dc1](https://bsd-hardware.info/?probe=4fb8582dc1) | Apr 24, 2021 |
| HP            | Laptop 17-by0xxx            | [4f4a6b1ab0](https://bsd-hardware.info/?probe=4f4a6b1ab0) | Apr 24, 2021 |
| Dell          | Precision 5520              | [7d5f7b5033](https://bsd-hardware.info/?probe=7d5f7b5033) | Apr 23, 2021 |
| Alienware     | M15x                        | [0b60c1cb25](https://bsd-hardware.info/?probe=0b60c1cb25) | Apr 22, 2021 |
| Dell          | Latitude 5580               | [f967516613](https://bsd-hardware.info/?probe=f967516613) | Apr 20, 2021 |
| Deciso        | Netboard A20                | [29856c2092](https://bsd-hardware.info/?probe=29856c2092) | Apr 19, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | [4faceaf6e5](https://bsd-hardware.info/?probe=4faceaf6e5) | Apr 17, 2021 |
| Dell          | XPS 13 9360                 | [f8bfc70f13](https://bsd-hardware.info/?probe=f8bfc70f13) | Apr 13, 2021 |
| Lenovo        | ThinkPad T400 7417TPU       | [981517a51a](https://bsd-hardware.info/?probe=981517a51a) | Apr 13, 2021 |
| Dell          | Latitude D610               | [d2cbb1f229](https://bsd-hardware.info/?probe=d2cbb1f229) | Apr 12, 2021 |
| Dell          | Inspiron 3521               | [9050866fb2](https://bsd-hardware.info/?probe=9050866fb2) | Apr 12, 2021 |
| Deciso        | Netboard A20                | [209a39e5ae](https://bsd-hardware.info/?probe=209a39e5ae) | Apr 11, 2021 |
| Deciso        | Netboard A20                | [9bfa19b9dc](https://bsd-hardware.info/?probe=9bfa19b9dc) | Apr 10, 2021 |
| Lenovo        | ThinkPad A485 20MUS07E00    | [812939c17f](https://bsd-hardware.info/?probe=812939c17f) | Apr 05, 2021 |
| Lenovo        | ThinkPad A485 20MUS07E00    | [22b35a127a](https://bsd-hardware.info/?probe=22b35a127a) | Apr 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | [2de4bc8337](https://bsd-hardware.info/?probe=2de4bc8337) | Apr 04, 2021 |
| Dell          | Latitude E5420              | [be14a1d28e](https://bsd-hardware.info/?probe=be14a1d28e) | Apr 04, 2021 |
| Deciso        | Netboard A20                | [a3057b99f1](https://bsd-hardware.info/?probe=a3057b99f1) | Apr 02, 2021 |
| Sony          | VGN-FW290J                  | [4a6ca78bc0](https://bsd-hardware.info/?probe=4a6ca78bc0) | Apr 01, 2021 |
| HP            | ProBook 640 G1              | [6bc6c5b2bf](https://bsd-hardware.info/?probe=6bc6c5b2bf) | Mar 31, 2021 |
| Deciso        | Netboard A20                | [a096d54ca7](https://bsd-hardware.info/?probe=a096d54ca7) | Mar 27, 2021 |
| Dell          | Precision M4600             | [04fb75b4ea](https://bsd-hardware.info/?probe=04fb75b4ea) | Mar 26, 2021 |
| Lenovo        | ThinkPad Edge 05796AU       | [4a094815c0](https://bsd-hardware.info/?probe=4a094815c0) | Mar 24, 2021 |
| Lenovo        | ThinkPad R61 77331CU        | [d223a9b1fb](https://bsd-hardware.info/?probe=d223a9b1fb) | Mar 23, 2021 |
| ASUSTek       | 900A                        | [e920222f0e](https://bsd-hardware.info/?probe=e920222f0e) | Mar 23, 2021 |
| ASUSTek       | 900A                        | [a76303a060](https://bsd-hardware.info/?probe=a76303a060) | Mar 21, 2021 |
| Apple         | MacBookPro6,2               | [d0b3b5da10](https://bsd-hardware.info/?probe=d0b3b5da10) | Mar 21, 2021 |
| Dell          | Latitude 5580               | [175191ccff](https://bsd-hardware.info/?probe=175191ccff) | Mar 18, 2021 |
| Dell          | Latitude 5580               | [f6225cf8d8](https://bsd-hardware.info/?probe=f6225cf8d8) | Mar 18, 2021 |
| DFI           | BE17X(170/171/173)          | [9e0509bd54](https://bsd-hardware.info/?probe=9e0509bd54) | Mar 18, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [bec05a34de](https://bsd-hardware.info/?probe=bec05a34de) | Mar 18, 2021 |
| Gateway       | Solo 450                    | [41e40c653e](https://bsd-hardware.info/?probe=41e40c653e) | Mar 16, 2021 |
| Lenovo        | ThinkPad T61 766416U        | [cf75f7c9cb](https://bsd-hardware.info/?probe=cf75f7c9cb) | Mar 13, 2021 |
| Lenovo        | ThinkPad T61 766416U        | [b90180457c](https://bsd-hardware.info/?probe=b90180457c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T530 2392ASU       | [39f3a4f234](https://bsd-hardware.info/?probe=39f3a4f234) | Mar 09, 2021 |
| Gateway       | Solo 450                    | [5dcb6e0ef6](https://bsd-hardware.info/?probe=5dcb6e0ef6) | Mar 09, 2021 |
| HP            | ProBook 450 G2              | [9f4a3cd83d](https://bsd-hardware.info/?probe=9f4a3cd83d) | Mar 08, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [5375f351a5](https://bsd-hardware.info/?probe=5375f351a5) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| ASUSTek       | X55CR                       | [e887ee2ff5](https://bsd-hardware.info/?probe=e887ee2ff5) | Mar 03, 2021 |
| ASUSTek       | X55CR                       | [e1e4548d22](https://bsd-hardware.info/?probe=e1e4548d22) | Mar 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6a4b5b90b7](https://bsd-hardware.info/?probe=6a4b5b90b7) | Mar 02, 2021 |
| Lenovo        | ThinkPad T490 20N3X50500    | [5f4ec887b6](https://bsd-hardware.info/?probe=5f4ec887b6) | Mar 02, 2021 |
| Acer          | Spin SP111-32N              | [9f44af71aa](https://bsd-hardware.info/?probe=9f44af71aa) | Feb 28, 2021 |
| Dell          | Inspiron 1000               | [70604dcbfa](https://bsd-hardware.info/?probe=70604dcbfa) | Feb 28, 2021 |
| Dell          | Latitude 5580               | [ab4ea78367](https://bsd-hardware.info/?probe=ab4ea78367) | Feb 28, 2021 |
| ASUSTek       | X555LAB                     | [b0364fffaf](https://bsd-hardware.info/?probe=b0364fffaf) | Feb 25, 2021 |
| ASUSTek       | X555LAB                     | [45d57c2be0](https://bsd-hardware.info/?probe=45d57c2be0) | Feb 24, 2021 |
| Dell          | XPS 13 9333                 | [7c78b3d42a](https://bsd-hardware.info/?probe=7c78b3d42a) | Feb 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7f35ef7fa9](https://bsd-hardware.info/?probe=7f35ef7fa9) | Feb 23, 2021 |
| Dell          | Inspiron 910                | [047950e61b](https://bsd-hardware.info/?probe=047950e61b) | Feb 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 4... | [f8f9140d92](https://bsd-hardware.info/?probe=f8f9140d92) | Feb 21, 2021 |
| Acer          | AOA150                      | [91e5ec60b9](https://bsd-hardware.info/?probe=91e5ec60b9) | Feb 21, 2021 |
| IBM           | ThinkPad T42 2374K46        | [311f93ab37](https://bsd-hardware.info/?probe=311f93ab37) | Feb 20, 2021 |
| Dell          | Latitude E7450              | [0a8e2a2e29](https://bsd-hardware.info/?probe=0a8e2a2e29) | Feb 19, 2021 |
| ASUSTek       | G73Jh                       | [ba7fb8e83c](https://bsd-hardware.info/?probe=ba7fb8e83c) | Feb 19, 2021 |
| HP            | ProBook 440 G2              | [63038d613f](https://bsd-hardware.info/?probe=63038d613f) | Feb 19, 2021 |
| Dell          | Inspiron 3521               | [10490aef33](https://bsd-hardware.info/?probe=10490aef33) | Feb 17, 2021 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [12c985b708](https://bsd-hardware.info/?probe=12c985b708) | Feb 17, 2021 |
| ASUSTek       | G73Jh                       | [35164ad41b](https://bsd-hardware.info/?probe=35164ad41b) | Feb 17, 2021 |
| Acer          | Spin SP111-32N              | [dd7644026b](https://bsd-hardware.info/?probe=dd7644026b) | Feb 16, 2021 |
| Lenovo        | ThinkPad T430 23427YU       | [79d1896352](https://bsd-hardware.info/?probe=79d1896352) | Feb 16, 2021 |
| MOTILE        | M142                        | [5ec101bb3e](https://bsd-hardware.info/?probe=5ec101bb3e) | Feb 15, 2021 |
| Apple         | MacBookPro6,2               | [4d83633f97](https://bsd-hardware.info/?probe=4d83633f97) | Feb 15, 2021 |
| Dell          | G7 7500                     | [a1c2eaee5f](https://bsd-hardware.info/?probe=a1c2eaee5f) | Feb 14, 2021 |
| Dell          | Inspiron 1000               | [104175ae13](https://bsd-hardware.info/?probe=104175ae13) | Feb 13, 2021 |
| Dell          | Inspiron 3521               | [3a73ecd855](https://bsd-hardware.info/?probe=3a73ecd855) | Feb 12, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [c2c9931f74](https://bsd-hardware.info/?probe=c2c9931f74) | Feb 12, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [c9e6341e78](https://bsd-hardware.info/?probe=c9e6341e78) | Feb 12, 2021 |
| Dell          | Inspiron 3521               | [afd71fdf87](https://bsd-hardware.info/?probe=afd71fdf87) | Feb 12, 2021 |
| DFI           | BE17X(170/171/173)          | [63442140dd](https://bsd-hardware.info/?probe=63442140dd) | Feb 11, 2021 |
| Dell          | Inspiron 3521               | [b3569ebb39](https://bsd-hardware.info/?probe=b3569ebb39) | Feb 11, 2021 |
| Lenovo        | ThinkPad L512 25975XU       | [b4d22f4179](https://bsd-hardware.info/?probe=b4d22f4179) | Feb 10, 2021 |
| Lenovo        | 20QD0000US                  | [8d1c80c2cb](https://bsd-hardware.info/?probe=8d1c80c2cb) | Feb 09, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [55debb2f24](https://bsd-hardware.info/?probe=55debb2f24) | Feb 08, 2021 |
| Lenovo        | 20QD0000US                  | [77e80759a0](https://bsd-hardware.info/?probe=77e80759a0) | Feb 08, 2021 |
| System76      | Galago Pro                  | [8f39c38e2e](https://bsd-hardware.info/?probe=8f39c38e2e) | Feb 08, 2021 |
| Chuwi         | CoreBox X                   | [2e51dfe463](https://bsd-hardware.info/?probe=2e51dfe463) | Feb 07, 2021 |
| Chuwi         | CoreBox X                   | [be6f23d3ed](https://bsd-hardware.info/?probe=be6f23d3ed) | Feb 07, 2021 |
| Apple         | MacBookPro8,2               | [ad4260feeb](https://bsd-hardware.info/?probe=ad4260feeb) | Feb 02, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [c69095f46d](https://bsd-hardware.info/?probe=c69095f46d) | Feb 02, 2021 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [faa7becf82](https://bsd-hardware.info/?probe=faa7becf82) | Feb 01, 2021 |
| Apple         | MacBookPro6,2               | [6174748602](https://bsd-hardware.info/?probe=6174748602) | Feb 01, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [dbc05e2913](https://bsd-hardware.info/?probe=dbc05e2913) | Jan 30, 2021 |
| Dell          | Latitude E5570              | [bcf60e66d7](https://bsd-hardware.info/?probe=bcf60e66d7) | Jan 26, 2021 |
| Acer          | Aspire 5515                 | [d9ef473a7a](https://bsd-hardware.info/?probe=d9ef473a7a) | Jan 25, 2021 |
| System76      | Bonobo Extreme              | [8e91df5bb8](https://bsd-hardware.info/?probe=8e91df5bb8) | Jan 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3444A... | [b659b95d1a](https://bsd-hardware.info/?probe=b659b95d1a) | Jan 18, 2021 |
| Dell          | Vostro 1510                 | [ef1c0e0f2e](https://bsd-hardware.info/?probe=ef1c0e0f2e) | Jan 17, 2021 |
| HP            | OMEN by HP Laptop           | [14857eb6b7](https://bsd-hardware.info/?probe=14857eb6b7) | Jan 15, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [f32bbdaff3](https://bsd-hardware.info/?probe=f32bbdaff3) | Jan 13, 2021 |
| Sony          | VGN-FW290J                  | [6683d77c92](https://bsd-hardware.info/?probe=6683d77c92) | Jan 11, 2021 |
| Dell          | Latitude 7480               | [9c8bd9c479](https://bsd-hardware.info/?probe=9c8bd9c479) | Jan 04, 2021 |
| Dell          | Latitude 7480               | [78d3823932](https://bsd-hardware.info/?probe=78d3823932) | Jan 04, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [c5e7d3037f](https://bsd-hardware.info/?probe=c5e7d3037f) | Jan 03, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [bb0846a279](https://bsd-hardware.info/?probe=bb0846a279) | Dec 30, 2020 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [6491c362f0](https://bsd-hardware.info/?probe=6491c362f0) | Dec 29, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [b6ae43880d](https://bsd-hardware.info/?probe=b6ae43880d) | Dec 22, 2020 |
| HP            | 2000                        | [f83c769501](https://bsd-hardware.info/?probe=f83c769501) | Dec 18, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [d019e14245](https://bsd-hardware.info/?probe=d019e14245) | Dec 18, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [c4d6dd6438](https://bsd-hardware.info/?probe=c4d6dd6438) | Dec 16, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [7b7c8bf457](https://bsd-hardware.info/?probe=7b7c8bf457) | Dec 16, 2020 |
| Toshiba       | Satellite C655D             | [23ca402ed6](https://bsd-hardware.info/?probe=23ca402ed6) | Dec 16, 2020 |
| Lenovo        | IdeaPad Slim 7 14IIL05 8... | [3278083ba9](https://bsd-hardware.info/?probe=3278083ba9) | Dec 16, 2020 |
| Dell          | XPS 15 9570                 | [91c4a075a1](https://bsd-hardware.info/?probe=91c4a075a1) | Dec 16, 2020 |
| Lenovo        | ThinkPad T450 20BV0064US    | [b397848c7e](https://bsd-hardware.info/?probe=b397848c7e) | Dec 16, 2020 |
| Lenovo        | G50-80 80E5                 | [61c248a1e6](https://bsd-hardware.info/?probe=61c248a1e6) | Dec 16, 2020 |
| Toshiba       | Satellite C855              | [6bc78fc7fc](https://bsd-hardware.info/?probe=6bc78fc7fc) | Dec 16, 2020 |
| Lenovo        | ThinkPad T420s 417153U      | [7af178dcda](https://bsd-hardware.info/?probe=7af178dcda) | Dec 15, 2020 |
| Eluktronic... | THINN-15                    | [b898297110](https://bsd-hardware.info/?probe=b898297110) | Dec 10, 2020 |
| Eluktronic... | THINN-15                    | [78bab7cda9](https://bsd-hardware.info/?probe=78bab7cda9) | Dec 10, 2020 |
| Acer          | Peppy                       | [d15caaca04](https://bsd-hardware.info/?probe=d15caaca04) | Dec 08, 2020 |
| Dell          | Latitude 3300               | [108a030875](https://bsd-hardware.info/?probe=108a030875) | Dec 07, 2020 |
| Apple         | MacBookPro11,3              | [26f15a2838](https://bsd-hardware.info/?probe=26f15a2838) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [21d88f733e](https://bsd-hardware.info/?probe=21d88f733e) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [cdfcd11f7b](https://bsd-hardware.info/?probe=cdfcd11f7b) | Dec 07, 2020 |
| Lenovo        | ThinkPad T410 2537NB5       | [d6a3aa6f8d](https://bsd-hardware.info/?probe=d6a3aa6f8d) | Dec 06, 2020 |
| Lenovo        | ThinkPad R400 7439X13       | [0d85bf3f3a](https://bsd-hardware.info/?probe=0d85bf3f3a) | Dec 03, 2020 |
| MSI           | X460/X460DX                 | [099fbcbec8](https://bsd-hardware.info/?probe=099fbcbec8) | Dec 01, 2020 |
| HP            | ProBook 640 G1              | [8f36943974](https://bsd-hardware.info/?probe=8f36943974) | Nov 29, 2020 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [624be8f7d6](https://bsd-hardware.info/?probe=624be8f7d6) | Nov 16, 2020 |
| HP            | ProBook 640 G1              | [bf763e72ad](https://bsd-hardware.info/?probe=bf763e72ad) | Nov 13, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [bfd9130d4b](https://bsd-hardware.info/?probe=bfd9130d4b) | Nov 10, 2020 |
| HP            | ProBook 650 G2              | [b6c63ea3f8](https://bsd-hardware.info/?probe=b6c63ea3f8) | Nov 09, 2020 |
| HP            | ProBook 650 G2              | [0d5f2584b7](https://bsd-hardware.info/?probe=0d5f2584b7) | Nov 09, 2020 |
| System76      | Serval WS                   | [0ac6aed43b](https://bsd-hardware.info/?probe=0ac6aed43b) | Nov 09, 2020 |
| System76      | Bonobo Extreme              | [de33b2c793](https://bsd-hardware.info/?probe=de33b2c793) | Nov 09, 2020 |
| System76      | Serval WS                   | [b23f15f795](https://bsd-hardware.info/?probe=b23f15f795) | Nov 09, 2020 |
| Apple         | MacBookPro6,2               | [81e299fd14](https://bsd-hardware.info/?probe=81e299fd14) | Nov 03, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | [ded161fe2e](https://bsd-hardware.info/?probe=ded161fe2e) | Oct 31, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | [e108d4a375](https://bsd-hardware.info/?probe=e108d4a375) | Oct 31, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [0a6ee35d3a](https://bsd-hardware.info/?probe=0a6ee35d3a) | Oct 28, 2020 |
| Lenovo        | ThinkPad T450 20BV0005US    | [603e66300a](https://bsd-hardware.info/?probe=603e66300a) | Oct 27, 2020 |
| Toshiba       | Satellite C655D             | [4492d307fc](https://bsd-hardware.info/?probe=4492d307fc) | Oct 25, 2020 |
| Lenovo        | Unknown                     | [7bab490506](https://bsd-hardware.info/?probe=7bab490506) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [03602ed2c0](https://bsd-hardware.info/?probe=03602ed2c0) | Oct 23, 2020 |
| Lenovo        | Unknown                     | [c659708e94](https://bsd-hardware.info/?probe=c659708e94) | Oct 23, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | [82398321f6](https://bsd-hardware.info/?probe=82398321f6) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | [1cc3cc20e8](https://bsd-hardware.info/?probe=1cc3cc20e8) | Oct 21, 2020 |
| Dell          | Latitude E7240              | [0e736e5e31](https://bsd-hardware.info/?probe=0e736e5e31) | Oct 20, 2020 |
| ASUSTek       | G551JW                      | [594e6f28fb](https://bsd-hardware.info/?probe=594e6f28fb) | Oct 19, 2020 |
| Acer          | Aspire one                  | [8514ff3ee8](https://bsd-hardware.info/?probe=8514ff3ee8) | Oct 14, 2020 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [ec1fa2e60c](https://bsd-hardware.info/?probe=ec1fa2e60c) | Oct 13, 2020 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [655613c78b](https://bsd-hardware.info/?probe=655613c78b) | Oct 04, 2020 |
| Dell          | Latitude E7240              | [fe74f6600f](https://bsd-hardware.info/?probe=fe74f6600f) | Oct 03, 2020 |
| Dell          | Precision 7530              | [717309ee39](https://bsd-hardware.info/?probe=717309ee39) | Sep 28, 2020 |
| Dell          | Precision 7530              | [6a2635237f](https://bsd-hardware.info/?probe=6a2635237f) | Sep 28, 2020 |
| Dell          | Precision 5510              | [a167382d6e](https://bsd-hardware.info/?probe=a167382d6e) | Sep 26, 2020 |
| Dell          | Precision 5510              | [621d3ea7a0](https://bsd-hardware.info/?probe=621d3ea7a0) | Sep 26, 2020 |
| Dell          | Precision 5510              | [837ffdd649](https://bsd-hardware.info/?probe=837ffdd649) | Sep 26, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [f7d13e4696](https://bsd-hardware.info/?probe=f7d13e4696) | Sep 23, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [45f410f4e4](https://bsd-hardware.info/?probe=45f410f4e4) | Sep 23, 2020 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [4d2c24a0e3](https://bsd-hardware.info/?probe=4d2c24a0e3) | Sep 15, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [fbf90aaf0d](https://bsd-hardware.info/?probe=fbf90aaf0d) | Sep 11, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [e06815d9dc](https://bsd-hardware.info/?probe=e06815d9dc) | Sep 11, 2020 |
| Toshiba       | Satellite C75D-B            | [9fb68e38d8](https://bsd-hardware.info/?probe=9fb68e38d8) | Sep 10, 2020 |
| Dell          | Precision M4800             | [ce29daf5ad](https://bsd-hardware.info/?probe=ce29daf5ad) | Sep 05, 2020 |
| Dell          | Precision M4800             | [1565096482](https://bsd-hardware.info/?probe=1565096482) | Sep 04, 2020 |
| Dell          | Precision M4800             | [ec0e767276](https://bsd-hardware.info/?probe=ec0e767276) | Sep 04, 2020 |
| Lenovo        | ThinkPad T420 4180MNU       | [4ea892826e](https://bsd-hardware.info/?probe=4ea892826e) | Sep 02, 2020 |
| Lenovo        | ThinkPad T495 20NJ0002US    | [0f7fdfb5f8](https://bsd-hardware.info/?probe=0f7fdfb5f8) | Sep 01, 2020 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [309d82d225](https://bsd-hardware.info/?probe=309d82d225) | Aug 29, 2020 |
| IBM           | ThinkPad T42 2374K46        | [bdd45acd8d](https://bsd-hardware.info/?probe=bdd45acd8d) | Aug 29, 2020 |
| Lenovo        | ThinkPad T60 20076PU        | [522182f3c4](https://bsd-hardware.info/?probe=522182f3c4) | Aug 29, 2020 |
| ASUSTek       | K53SD                       | [975e9ccbe2](https://bsd-hardware.info/?probe=975e9ccbe2) | Aug 27, 2020 |
| Lenovo        | ThinkPad T530 239242U       | [7c8087322d](https://bsd-hardware.info/?probe=7c8087322d) | Aug 27, 2020 |
| Google        | Link                        | [ad371b5358](https://bsd-hardware.info/?probe=ad371b5358) | Aug 22, 2020 |
| Dell          | Latitude 2100               | [13dd55a097](https://bsd-hardware.info/?probe=13dd55a097) | Aug 20, 2020 |
| Razer         | Blade Stealth               | [a467ffacf3](https://bsd-hardware.info/?probe=a467ffacf3) | Aug 17, 2020 |
| Razer         | Blade Stealth               | [37b1b5d950](https://bsd-hardware.info/?probe=37b1b5d950) | Aug 17, 2020 |
| Unknown       | Unknown                     | [2dca4f98fc](https://bsd-hardware.info/?probe=2dca4f98fc) | Aug 17, 2020 |
| Apple         | MacBookAir4,1               | [b517071f26](https://bsd-hardware.info/?probe=b517071f26) | Aug 15, 2020 |
| Apple         | MacBookPro8,3               | [052524523b](https://bsd-hardware.info/?probe=052524523b) | Aug 15, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | [90e154cf08](https://bsd-hardware.info/?probe=90e154cf08) | Aug 14, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | [c98c08b739](https://bsd-hardware.info/?probe=c98c08b739) | Aug 14, 2020 |
| System76      | Kudu                        | [418b97d56f](https://bsd-hardware.info/?probe=418b97d56f) | Aug 14, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [ce9330472e](https://bsd-hardware.info/?probe=ce9330472e) | Aug 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [a215fde229](https://bsd-hardware.info/?probe=a215fde229) | Aug 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [ce38287004](https://bsd-hardware.info/?probe=ce38287004) | Aug 13, 2020 |
| HP            | ProBook 640 G1              | [4b7eaf5a6a](https://bsd-hardware.info/?probe=4b7eaf5a6a) | Aug 12, 2020 |
| HP            | EliteBook 820 G1            | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [37a42caa92](https://bsd-hardware.info/?probe=37a42caa92) | Jul 30, 2020 |
| HP            | Laptop 15-bs0xx             | [4cfc4cff49](https://bsd-hardware.info/?probe=4cfc4cff49) | Jul 28, 2020 |
| Dell          | Inspiron 3521               | [300cbce244](https://bsd-hardware.info/?probe=300cbce244) | Jul 26, 2020 |
| Timi          | RedmiBook 14 II             | [a7bf2669ce](https://bsd-hardware.info/?probe=a7bf2669ce) | Jul 24, 2020 |
| Dell          | Precision M4800             | [bbd03815ce](https://bsd-hardware.info/?probe=bbd03815ce) | Jul 20, 2020 |
| Toshiba       | Satellite C655D             | [191b32d117](https://bsd-hardware.info/?probe=191b32d117) | Jul 17, 2020 |
| Toshiba       | Satellite C655D             | [981c74a766](https://bsd-hardware.info/?probe=981c74a766) | Jul 15, 2020 |
| Dell          | Precision 7550              | [9983a81086](https://bsd-hardware.info/?probe=9983a81086) | Jul 10, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [b726c4536b](https://bsd-hardware.info/?probe=b726c4536b) | Jul 04, 2020 |
| Acer          | Peppy                       | [f5bf2c1fc7](https://bsd-hardware.info/?probe=f5bf2c1fc7) | Jun 18, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [2d0dc32ced](https://bsd-hardware.info/?probe=2d0dc32ced) | Jun 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dfef5fdcbf](https://bsd-hardware.info/?probe=dfef5fdcbf) | Jun 10, 2020 |
| Dell          | Latitude E6410              | [996540c1dc](https://bsd-hardware.info/?probe=996540c1dc) | Jun 04, 2020 |
| Toshiba       | Satellite L775D             | [bb218a14a6](https://bsd-hardware.info/?probe=bb218a14a6) | Jun 03, 2020 |
| Toshiba       | Satellite L775D             | [f0ec90217a](https://bsd-hardware.info/?probe=f0ec90217a) | Jun 03, 2020 |
| Dell          | Latitude E6320              | [2ebfa76c28](https://bsd-hardware.info/?probe=2ebfa76c28) | Jun 01, 2020 |
| Lenovo        | ThinkPad X220 42872WU       | [a95465cdda](https://bsd-hardware.info/?probe=a95465cdda) | May 29, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0H70... | [dfd9a97efc](https://bsd-hardware.info/?probe=dfd9a97efc) | May 27, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0H70... | [0c4faa7698](https://bsd-hardware.info/?probe=0c4faa7698) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | [6ea713bf51](https://bsd-hardware.info/?probe=6ea713bf51) | May 25, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | [7b67911c5a](https://bsd-hardware.info/?probe=7b67911c5a) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b4ca8bbc46](https://bsd-hardware.info/?probe=b4ca8bbc46) | May 25, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | [916596bfa8](https://bsd-hardware.info/?probe=916596bfa8) | May 25, 2020 |
| Lenovo        | ThinkPad T430s 23539LU      | [eab6164233](https://bsd-hardware.info/?probe=eab6164233) | May 23, 2020 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [9ff1537692](https://bsd-hardware.info/?probe=9ff1537692) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [8ed0fee673](https://bsd-hardware.info/?probe=8ed0fee673) | May 22, 2020 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [010db0aed4](https://bsd-hardware.info/?probe=010db0aed4) | May 22, 2020 |
| Lenovo        | ThinkPad T440p 20AWS07F0... | [9001a6ea5b](https://bsd-hardware.info/?probe=9001a6ea5b) | May 22, 2020 |
| Lenovo        | ThinkPad T440p 20AWS07F0... | [79ec87b2db](https://bsd-hardware.info/?probe=79ec87b2db) | May 22, 2020 |
| Dell          | Precision 7540              | [aa891d8f27](https://bsd-hardware.info/?probe=aa891d8f27) | May 22, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 31        | 7.05%   |
| FreeBSD 13.0         | 28        | 6.36%   |
| helloSystem 0.5.0    | 20        | 4.55%   |
| FreeBSD 13.1         | 19        | 4.32%   |
| OpenBSD 6.9          | 14        | 3.18%   |
| OpenBSD 6.8          | 14        | 3.18%   |
| helloSystem 0.4.0    | 14        | 3.18%   |
| GhostBSD 20.04.02    | 13        | 2.95%   |
| FreeBSD 14.0-CURRENT | 12        | 2.73%   |
| FreeBSD 12.1-p8      | 12        | 2.73%   |
| FreeBSD 13.0-p4      | 11        | 2.5%    |
| FreeBSD 12.2         | 10        | 2.27%   |
| OpenBSD 7.0          | 8         | 1.82%   |
| GhostBSD 21.08.27    | 7         | 1.59%   |
| FreeBSD 12.2-p2      | 7         | 1.59%   |
| OpenBSD 6.7          | 6         | 1.36%   |
| NomadBSD 5806f915    | 6         | 1.36%   |
| NomadBSD 1.3.2       | 6         | 1.36%   |
| helloSystem 0.6.0    | 6         | 1.36%   |
| FreeBSD 13.0-STABLE  | 6         | 1.36%   |
| FreeBSD 13.0-p2      | 6         | 1.36%   |
| FreeBSD 12.2-p3      | 6         | 1.36%   |
| FreeBSD 13.1-p2      | 5         | 1.14%   |
| FreeBSD 13.0-p11     | 5         | 1.14%   |
| FreeBSD 12.2-p4      | 5         | 1.14%   |
| FreeBSD 12.1-p10     | 5         | 1.14%   |
| FreeBSD 12.1         | 5         | 1.14%   |
| OPNsense 21.7.7      | 4         | 0.91%   |
| OPNsense 21.1        | 4         | 0.91%   |
| helloSystem 0.8.0    | 4         | 0.91%   |
| FreeBSD 13.0-p7      | 4         | 0.91%   |
| FreeBSD 13.0-p5      | 4         | 0.91%   |
| FreeBSD 13.0-p3      | 4         | 0.91%   |
| FreeBSD 13.0-CURRENT | 4         | 0.91%   |
| FreeBSD 12.2-p6      | 4         | 0.91%   |
| OPNsense 22.7.4      | 3         | 0.68%   |
| OPNsense 22.1.7      | 3         | 0.68%   |
| OPNsense 22.1.5      | 3         | 0.68%   |
| OPNsense 22.1.10     | 3         | 0.68%   |
| OPNsense 22.1        | 3         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 179       | 47.23%  |
| helloSystem | 72        | 19%     |
| OpenBSD     | 45        | 11.87%  |
| OPNsense    | 32        | 8.44%   |
| GhostBSD    | 26        | 6.86%   |
| NomadBSD    | 13        | 3.43%   |
| HardenedBSD | 4         | 1.06%   |
| MidnightBSD | 3         | 0.79%   |
| DragonFly   | 3         | 0.79%   |
| NetBSD      | 1         | 0.26%   |
| FuryBSD     | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 353       | 94.89%  |
| i386  | 18        | 4.84%   |
| arm64 | 1         | 0.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 72        | 18.46%  |
| XFCE          | 53        | 13.59%  |
| Console       | 53        | 13.59%  |
| fvwm          | 38        | 9.74%   |
| MATE          | 35        | 8.97%   |
| KDE5          | 33        | 8.46%   |
| TWM           | 26        | 6.67%   |
| GNOME         | 20        | 5.13%   |
| Openbox       | 19        | 4.87%   |
| i3            | 14        | 3.59%   |
| Cinnamon      | 6         | 1.54%   |
| Fluxbox       | 4         | 1.03%   |
| Enlightenment | 4         | 1.03%   |
| AwesomeWM     | 3         | 0.77%   |
| GNUstep       | 2         | 0.51%   |
| Xfwm4         | 1         | 0.26%   |
| spectrwm      | 1         | 0.26%   |
| LXQt          | 1         | 0.26%   |
| LXDE          | 1         | 0.26%   |
| Lumina        | 1         | 0.26%   |
| DWM           | 1         | 0.26%   |
| Compton       | 1         | 0.26%   |
| CDE           | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 311       | 82.93%  |
| Console | 61        | 16.27%  |
| Wayland | 3         | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 153       | 39.43%  |
| SLiM    | 128       | 32.99%  |
| LightDM | 39        | 10.05%  |
| SDDM    | 36        | 9.28%   |
| XDM     | 16        | 4.12%   |
| GDM     | 14        | 3.61%   |
| Ly      | 2         | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 142       | 36.69%  |
| en_US           | 135       | 34.88%  |
| C               | 104       | 26.87%  |
| en_US.US-ASCII  | 2         | 0.52%   |
| es_CO           | 1         | 0.26%   |
| en_US.ISO8859-1 | 1         | 0.26%   |
| en_GB           | 1         | 0.26%   |
| de_DE           | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 272       | 72.15%  |
| BIOS | 105       | 27.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 208       | 54.45%  |
| Ufs     | 105       | 27.49%  |
| Ffs     | 45        | 11.78%  |
| Cd9660  | 21        | 5.5%    |
| Hammer2 | 3         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 319       | 84.39%  |
| MBR     | 52        | 13.76%  |
| Unknown | 5         | 1.32%   |
| BSD     | 2         | 0.53%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 127       | 34.32%  |
| Dell                | 78        | 21.08%  |
| Hewlett-Packard     | 43        | 11.62%  |
| Apple               | 20        | 5.41%   |
| ASUSTek Computer    | 17        | 4.59%   |
| Deciso              | 14        | 3.78%   |
| Acer                | 11        | 2.97%   |
| System76            | 10        | 2.7%    |
| Toshiba             | 9         | 2.43%   |
| Framework           | 6         | 1.62%   |
| MSI                 | 4         | 1.08%   |
| Unknown             | 4         | 1.08%   |
| Timi                | 2         | 0.54%   |
| Sony                | 2         | 0.54%   |
| Samsung Electronics | 2         | 0.54%   |
| IBM                 | 2         | 0.54%   |
| Google              | 2         | 0.54%   |
| Gateway             | 2         | 0.54%   |
| Datto               | 2         | 0.54%   |
| Valve               | 1         | 0.27%   |
| TUXEDO              | 1         | 0.27%   |
| Razer               | 1         | 0.27%   |
| Notebook            | 1         | 0.27%   |
| MOTILE              | 1         | 0.27%   |
| LG Electronics      | 1         | 0.27%   |
| GPU Company         | 1         | 0.27%   |
| GPD                 | 1         | 0.27%   |
| Gigabyte Technology | 1         | 0.27%   |
| Eluktronics         | 1         | 0.27%   |
| DFI                 | 1         | 0.27%   |
| Chuwi               | 1         | 0.27%   |
| Alienware           | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Deciso Netboard A20                     | 10        | 2.7%    |
| Framework Laptop                        | 6         | 1.62%   |
| Dell Inspiron 3521                      | 5         | 1.35%   |
| Unknown                                 | 5         | 1.35%   |
| Lenovo ThinkPad X220 4286CTO            | 3         | 0.81%   |
| HP Pavilion dv6                         | 3         | 0.81%   |
| HP 2000                                 | 3         | 0.81%   |
| Dell Latitude E7240                     | 3         | 0.81%   |
| Dell Latitude E6420                     | 3         | 0.81%   |
| Dell Latitude E5420                     | 3         | 0.81%   |
| Apple MacBookPro6,2                     | 3         | 0.81%   |
| Toshiba PORTEGE R700                    | 2         | 0.54%   |
| System76 Kudu                           | 2         | 0.54%   |
| System76 Gazelle                        | 2         | 0.54%   |
| System76 Galago Pro                     | 2         | 0.54%   |
| System76 Bonobo Extreme                 | 2         | 0.54%   |
| Lenovo ThinkPad X250 20CLS1WP01         | 2         | 0.54%   |
| Lenovo ThinkPad X220 42872WU            | 2         | 0.54%   |
| Lenovo ThinkPad W530 2436CTO            | 2         | 0.54%   |
| Lenovo ThinkPad T60 20076PU             | 2         | 0.54%   |
| Lenovo ThinkPad T430s 2352CTO           | 2         | 0.54%   |
| Dell Precision M4800                    | 2         | 0.54%   |
| Dell Precision 7710                     | 2         | 0.54%   |
| Dell Precision 7550                     | 2         | 0.54%   |
| Dell Precision 7540                     | 2         | 0.54%   |
| Dell Latitude E7450                     | 2         | 0.54%   |
| Dell Latitude D630                      | 2         | 0.54%   |
| Dell Latitude 2100                      | 2         | 0.54%   |
| Deciso NetBoard-A10                     | 2         | 0.54%   |
| Datto 1000                              | 2         | 0.54%   |
| ASUS VivoBook_ASUSLaptop X712DAP_M712DA | 2         | 0.54%   |
| ASUS G551JW                             | 2         | 0.54%   |
| Apple MacBookPro9,2                     | 2         | 0.54%   |
| Apple MacBookPro8,3                     | 2         | 0.54%   |
| Valve Jupiter                           | 1         | 0.27%   |
| TUXEDO Pulse 15 Gen1                    | 1         | 0.27%   |
| Toshiba Satellite P755                  | 1         | 0.27%   |
| Toshiba Satellite P25                   | 1         | 0.27%   |
| Toshiba Satellite L775D                 | 1         | 0.27%   |
| Toshiba Satellite L305D                 | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 109       | 29.46%  |
| Dell Latitude       | 31        | 8.38%   |
| Dell Inspiron       | 19        | 5.14%   |
| Dell Precision      | 13        | 3.51%   |
| HP Pavilion         | 11        | 2.97%   |
| Deciso Netboard     | 10        | 2.7%    |
| Lenovo IdeaPad      | 8         | 2.16%   |
| Toshiba Satellite   | 7         | 1.89%   |
| Dell XPS            | 7         | 1.89%   |
| HP ProBook          | 6         | 1.62%   |
| HP Laptop           | 6         | 1.62%   |
| Framework Laptop    | 6         | 1.62%   |
| HP EliteBook        | 5         | 1.35%   |
| Acer Aspire         | 5         | 1.35%   |
| Unknown             | 5         | 1.35%   |
| ASUS VivoBook       | 4         | 1.08%   |
| Apple MacBookPro8   | 4         | 1.08%   |
| Lenovo Legion       | 3         | 0.81%   |
| HP 2000             | 3         | 0.81%   |
| Apple MacBookPro9   | 3         | 0.81%   |
| Apple MacBookPro6   | 3         | 0.81%   |
| Toshiba PORTEGE     | 2         | 0.54%   |
| System76 Kudu       | 2         | 0.54%   |
| System76 Gazelle    | 2         | 0.54%   |
| System76 Galago     | 2         | 0.54%   |
| System76 Bonobo     | 2         | 0.54%   |
| Lenovo Flex         | 2         | 0.54%   |
| IBM ThinkPad        | 2         | 0.54%   |
| HP ZBook            | 2         | 0.54%   |
| HP Stream           | 2         | 0.54%   |
| HP OMEN             | 2         | 0.54%   |
| Dell Vostro         | 2         | 0.54%   |
| Dell Studio         | 2         | 0.54%   |
| Dell G3             | 2         | 0.54%   |
| Deciso NetBoard-A10 | 2         | 0.54%   |
| Datto 1000          | 2         | 0.54%   |
| ASUS G551JW         | 2         | 0.54%   |
| Valve Jupiter       | 1         | 0.27%   |
| TUXEDO Pulse        | 1         | 0.27%   |
| Timi TM1701         | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 51        | 13.78%  |
| 2021    | 41        | 11.08%  |
| 2011    | 36        | 9.73%   |
| 2015    | 34        | 9.19%   |
| 2019    | 31        | 8.38%   |
| 2018    | 26        | 7.03%   |
| 2016    | 23        | 6.22%   |
| 2013    | 20        | 5.41%   |
| 2012    | 18        | 4.86%   |
| 2010    | 15        | 4.05%   |
| 2014    | 14        | 3.78%   |
| 2009    | 13        | 3.51%   |
| 2017    | 12        | 3.24%   |
| 2022    | 10        | 2.7%    |
| 2008    | 9         | 2.43%   |
| 2007    | 6         | 1.62%   |
| 2006    | 6         | 1.62%   |
| 2004    | 2         | 0.54%   |
| 2005    | 1         | 0.27%   |
| 2002    | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 370       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 363       | 98.11%  |
| Yes  | 7         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 137       | 36.34%  |
| 16.01-24.0  | 92        | 24.4%   |
| 4.01-8.0    | 70        | 18.57%  |
| 32.01-64.0  | 28        | 7.43%   |
| 3.01-4.0    | 15        | 3.98%   |
| 2.01-3.0    | 15        | 3.98%   |
| 64.01-256.0 | 10        | 2.65%   |
| 24.01-32.0  | 4         | 1.06%   |
| 1.01-2.0    | 3         | 0.8%    |
| 0.51-1.0    | 2         | 0.53%   |
| 0.01-0.5    | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Notebooks | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 185       | 48.94%  |
| 0.51-1.0    | 113       | 29.89%  |
| 1.01-2.0    | 42        | 11.11%  |
| 2.01-3.0    | 17        | 4.5%    |
| 8.01-16.0   | 7         | 1.85%   |
| 4.01-8.0    | 4         | 1.06%   |
| 0           | 4         | 1.06%   |
| 16.01-24.0  | 2         | 0.53%   |
| 3.01-4.0    | 1         | 0.26%   |
| 24.01-32.0  | 1         | 0.26%   |
| 64.01-256.0 | 1         | 0.26%   |
| Unknown     | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 301       | 79.21%  |
| 2      | 54        | 14.21%  |
| 0      | 13        | 3.42%   |
| 3      | 11        | 2.89%   |
| 4      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 247       | 66.04%  |
| Yes       | 127       | 33.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 321       | 86.76%  |
| No        | 49        | 13.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 347       | 93.53%  |
| No        | 24        | 6.47%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 237       | 63.37%  |
| No        | 137       | 36.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| USA     | 370       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brooklyn       | 22        | 5.61%   |
| Seattle        | 9         | 2.3%    |
| Portland       | 8         | 2.04%   |
| New York       | 8         | 2.04%   |
| Los Angeles    | 8         | 2.04%   |
| Chicago        | 6         | 1.53%   |
| Washington     | 5         | 1.28%   |
| Vienna         | 4         | 1.02%   |
| Rochester      | 4         | 1.02%   |
| Harrisburg     | 4         | 1.02%   |
| Frisco         | 4         | 1.02%   |
| Whittier       | 3         | 0.77%   |
| Springfield    | 3         | 0.77%   |
| Queens         | 3         | 0.77%   |
| Phoenix        | 3         | 0.77%   |
| Omaha          | 3         | 0.77%   |
| Midvale        | 3         | 0.77%   |
| Eugene         | 3         | 0.77%   |
| Dublin         | 3         | 0.77%   |
| Dallas         | 3         | 0.77%   |
| Charlotte      | 3         | 0.77%   |
| Atlanta        | 3         | 0.77%   |
| Apex           | 3         | 0.77%   |
| Albuquerque    | 3         | 0.77%   |
| Ypsilanti      | 2         | 0.51%   |
| San Francisco  | 2         | 0.51%   |
| San Diego      | 2         | 0.51%   |
| San Bernardino | 2         | 0.51%   |
| San Antonio    | 2         | 0.51%   |
| Roswell        | 2         | 0.51%   |
| Riverside      | 2         | 0.51%   |
| Renton         | 2         | 0.51%   |
| Papillion      | 2         | 0.51%   |
| Palmer         | 2         | 0.51%   |
| Oklahoma City  | 2         | 0.51%   |
| New Braunfels  | 2         | 0.51%   |
| Memphis        | 2         | 0.51%   |
| Las Vegas      | 2         | 0.51%   |
| Lake Forest    | 2         | 0.51%   |
| Lafayette      | 2         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 75        | 91     | 17.56%  |
| WDC                 | 68        | 72     | 15.93%  |
| Crucial             | 30        | 39     | 7.03%   |
| Toshiba             | 26        | 33     | 6.09%   |
| Seagate             | 26        | 29     | 6.09%   |
| SanDisk             | 23        | 29     | 5.39%   |
| Transcend           | 21        | 37     | 4.92%   |
| Kingston            | 13        | 14     | 3.04%   |
| Intel               | 13        | 15     | 3.04%   |
| NVMe                | 12        | 16     | 2.81%   |
| Hitachi             | 12        | 14     | 2.81%   |
| SK hynix            | 9         | 9      | 2.11%   |
| Apple               | 9         | 9      | 2.11%   |
| PNY                 | 8         | 9      | 1.87%   |
| Phison              | 7         | 13     | 1.64%   |
| OWC                 | 7         | 8      | 1.64%   |
| Micron Technology   | 7         | 8      | 1.64%   |
| HGST                | 7         | 8      | 1.64%   |
| SPCC                | 5         | 5      | 1.17%   |
| KingSpec            | 5         | 5      | 1.17%   |
| Corsair             | 5         | 5      | 1.17%   |
| Zheino              | 3         | 6      | 0.7%    |
| SSSTC               | 3         | 3      | 0.7%    |
| Mushkin             | 3         | 3      | 0.7%    |
| A-DATA Technology   | 3         | 4      | 0.7%    |
| Patriot             | 2         | 2      | 0.47%   |
| Netac               | 2         | 2      | 0.47%   |
| Lexar               | 2         | 6      | 0.47%   |
| KIOXIA              | 2         | 2      | 0.47%   |
| Fujitsu             | 2         | 2      | 0.47%   |
| BIWIN               | 2         | 3      | 0.47%   |
| ZTC                 | 1         | 1      | 0.23%   |
| Team                | 1         | 2      | 0.23%   |
| T-FORCE             | 1         | 1      | 0.23%   |
| Silicon Motion      | 1         | 1      | 0.23%   |
| Plextor             | 1         | 1      | 0.23%   |
| OPENBSD             | 1         | 1      | 0.23%   |
| LITEONIT            | 1         | 1      | 0.23%   |
| LITEON              | 1         | 1      | 0.23%   |
| Lenovo              | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB       | 10        | 2.29%   |
| Crucial CT500MX500SSD1 500GB         | 9         | 2.06%   |
| Crucial CT1000MX500SSD1 1TB          | 6         | 1.38%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 5         | 1.15%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 1.15%   |
| Kingston SA400S37240G 240GB          | 5         | 1.15%   |
| WDC WDBNCE5000PNC 500GB              | 4         | 0.92%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.92%   |
| SanDisk SSD PLUS 240GB               | 4         | 0.92%   |
| Samsung SSD 970 EVO Plus 500GB       | 4         | 0.92%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 0.92%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.92%   |
| NVMe WDC PC SN730 SDB 256GB          | 4         | 0.92%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 3         | 0.69%   |
| Transcend TS128GMTS430S 128GB        | 3         | 0.69%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 0.69%   |
| Samsung SSD 850 PRO 512GB            | 3         | 0.69%   |
| Samsung SSD 850 EVO 1TB              | 3         | 0.69%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 3         | 0.69%   |
| Phison PCIe SSD 1TB                  | 3         | 0.69%   |
| Hitachi HTS547550A9E384 500GB        | 3         | 0.69%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.69%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.46%   |
| WDC WD1600BEVT-75ZCT2 160GB          | 2         | 0.46%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.46%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 2         | 0.46%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 0.46%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 2         | 0.46%   |
| Transcend TS256GMTE652T2 256GB       | 2         | 0.46%   |
| Toshiba KXG50ZNV256G NVMe 256GB      | 2         | 0.46%   |
| SSSTC CVB-8D128-HP 128GB             | 2         | 0.46%   |
| SPCC Solid State Disk 128GB          | 2         | 0.46%   |
| SK hynix SC311 SATA 256GB            | 2         | 0.46%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.46%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 0.46%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 0.46%   |
| SanDisk pSSD 16GB                    | 2         | 0.46%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 40     | 31.71%  |
| Seagate             | 26        | 29     | 21.14%  |
| Toshiba             | 20        | 27     | 16.26%  |
| Hitachi             | 12        | 14     | 9.76%   |
| NVMe                | 10        | 12     | 8.13%   |
| HGST                | 7         | 8      | 5.69%   |
| Apple               | 3         | 3      | 2.44%   |
| Fujitsu             | 2         | 2      | 1.63%   |
| Samsung Electronics | 1         | 2      | 0.81%   |
| OPENBSD             | 1         | 1      | 0.81%   |
| IBM/Hitachi         | 1         | 1      | 0.81%   |
| Generic             | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 50        | 55     | 22.94%  |
| Crucial             | 27        | 34     | 12.39%  |
| SanDisk             | 23        | 29     | 10.55%  |
| Transcend           | 18        | 34     | 8.26%   |
| WDC                 | 11        | 11     | 5.05%   |
| Kingston            | 11        | 11     | 5.05%   |
| PNY                 | 8         | 9      | 3.67%   |
| Intel               | 8         | 9      | 3.67%   |
| OWC                 | 7         | 8      | 3.21%   |
| Apple               | 6         | 6      | 2.75%   |
| SK hynix            | 5         | 5      | 2.29%   |
| KingSpec            | 5         | 5      | 2.29%   |
| Corsair             | 5         | 5      | 2.29%   |
| SPCC                | 4         | 4      | 1.83%   |
| Zheino              | 3         | 6      | 1.38%   |
| NVMe                | 3         | 3      | 1.38%   |
| SSSTC               | 2         | 2      | 0.92%   |
| Phison              | 2         | 2      | 0.92%   |
| Patriot             | 2         | 2      | 0.92%   |
| Netac               | 2         | 2      | 0.92%   |
| Mushkin             | 2         | 2      | 0.92%   |
| Lexar               | 2         | 6      | 0.92%   |
| BIWIN               | 2         | 3      | 0.92%   |
| A-DATA Technology   | 2         | 2      | 0.92%   |
| ZTC                 | 1         | 1      | 0.46%   |
| Team                | 1         | 2      | 0.46%   |
| Plextor             | 1         | 1      | 0.46%   |
| LITEONIT            | 1         | 1      | 0.46%   |
| Intenso             | 1         | 1      | 0.46%   |
| Hewlett-Packard     | 1         | 1      | 0.46%   |
| FLEXXON             | 1         | 3      | 0.46%   |
| China               | 1         | 1      | 0.46%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 196       | 266    | 49.37%  |
| HDD  | 121       | 140    | 30.48%  |
| NVMe | 80        | 113    | 20.15%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 300       | 406    | 78.95%  |
| NVMe | 80        | 113    | 21.05%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 229       | 299    | 72.01%  |
| 0.51-1.0   | 80        | 95     | 25.16%  |
| 1.01-2.0   | 9         | 12     | 2.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 133       | 34.46%  |
| 251-500    | 100       | 25.91%  |
| 1-20       | 65        | 16.84%  |
| 501-1000   | 43        | 11.14%  |
| 51-100     | 24        | 6.22%   |
| 21-50      | 9         | 2.33%   |
| 1001-2000  | 8         | 2.07%   |
| Unknown    | 3         | 0.78%   |
| 2001-3000  | 1         | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 321       | 83.59%  |
| 21-50   | 36        | 9.38%   |
| 51-100  | 12        | 3.13%   |
| 101-250 | 11        | 2.86%   |
| Unknown | 3         | 0.78%   |
| 251-500 | 1         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                              | Notebooks | Drives | Percent |
|----------------------------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB                    | 4         | 4      | 7.69%   |
| SSSTC CVB-8D128-HP 128GB                           | 2         | 2      | 3.85%   |
| WDC WD5000LPCX-75VHAT0 500GB                       | 1         | 1      | 1.92%   |
| WDC WD3200BPVT-75ZEST0 320GB                       | 1         | 1      | 1.92%   |
| WDC WD3200BPVT-75JJ5T0 320GB                       | 1         | 1      | 1.92%   |
| WDC WD3200BEKT-60V5T1 320GB                        | 1         | 1      | 1.92%   |
| WDC WD1600BEKT-66F3T2 160GB                        | 1         | 1      | 1.92%   |
| Toshiba MQ01ACF032 320GB                           | 1         | 1      | 1.92%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD075 752GB                           | 1         | 1      | 1.92%   |
| Toshiba MK7559GSXF 752GB                           | 1         | 1      | 1.92%   |
| Toshiba MK5061GSYN 500GB                           | 1         | 1      | 1.92%   |
| Toshiba MK3265GSXN 320GB                           | 1         | 5      | 1.92%   |
| Toshiba MK1637GSX 160GB                            | 1         | 2      | 1.92%   |
| SK hynix SC210 mSATA 256GB                         | 1         | 1      | 1.92%   |
| Seagate ST96023AS 58GB                             | 1         | 1      | 1.92%   |
| Seagate ST95005620AS 500GB                         | 1         | 1      | 1.92%   |
| Seagate ST9320423AS 320GB                          | 1         | 1      | 1.92%   |
| Seagate ST500LT012-9WS142 500GB                    | 1         | 1      | 1.92%   |
| Seagate ST320LT007-9ZV142 320GB                    | 1         | 1      | 1.92%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                 | 1         | 1      | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 2      | 1.92%   |
| SanDisk SSD PLUS 240GB                             | 1         | 1      | 1.92%   |
| SanDisk SD5SG2128G1052E 128GB                      | 1         | 1      | 1.92%   |
| Samsung Electronics SSD UM410 Series 2.5-inch 16GB | 1         | 1      | 1.92%   |
| Samsung Electronics SSD PM851 mSATA 256GB          | 1         | 1      | 1.92%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB       | 1         | 1      | 1.92%   |
| Samsung Electronics HM121HI 120GB                  | 1         | 2      | 1.92%   |
| Patriot Inferno 60GB SSD                           | 1         | 1      | 1.92%   |
| Kingston SV300S37A120G 120GB                       | 1         | 1      | 1.92%   |
| Kingston SNS4151S332G 32GB                         | 1         | 1      | 1.92%   |
| Kingston SMSM151S3128GD 128GB                      | 1         | 1      | 1.92%   |
| Kingston SA400S37240G 240GB                        | 1         | 1      | 1.92%   |
| KingSpec KSD-PA25.6-032MS 32GB                     | 1         | 1      | 1.92%   |
| Intel SSDSC2KW256G8 256GB                          | 1         | 1      | 1.92%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB                  | 1         | 1      | 1.92%   |
| Hitachi HTS722010K9SA00 100GB                      | 1         | 1      | 1.92%   |
| Hitachi HTS721080G9SA00 80GB                       | 1         | 1      | 1.92%   |
| Hitachi HTS547550A9E384 500GB                      | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 21.15%  |
| Toshiba             | 8         | 13     | 15.38%  |
| Hitachi             | 6         | 7      | 11.54%  |
| WDC                 | 5         | 5      | 9.62%   |
| Samsung Electronics | 4         | 5      | 7.69%   |
| Kingston            | 4         | 4      | 7.69%   |
| HGST                | 3         | 3      | 5.77%   |
| SSSTC               | 2         | 2      | 3.85%   |
| SanDisk             | 2         | 2      | 3.85%   |
| SK hynix            | 1         | 1      | 1.92%   |
| Patriot             | 1         | 1      | 1.92%   |
| KingSpec            | 1         | 1      | 1.92%   |
| Intel               | 1         | 1      | 1.92%   |
| IBM/Hitachi         | 1         | 1      | 1.92%   |
| Corsair             | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 30.56%  |
| Toshiba             | 8         | 13     | 22.22%  |
| Hitachi             | 6         | 7      | 16.67%  |
| WDC                 | 5         | 5      | 13.89%  |
| HGST                | 3         | 3      | 8.33%   |
| Samsung Electronics | 1         | 2      | 2.78%   |
| IBM/Hitachi         | 1         | 1      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 44     | 69.23%  |
| SSD  | 16        | 16     | 30.77%  |

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
| Works    | 308       | 440    | 82.35%  |
| Malfunc  | 52        | 60     | 13.9%   |
| Detected | 14        | 19     | 3.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 261       | 63.2%   |
| AMD                              | 51        | 12.35%  |
| Samsung Electronics              | 31        | 7.51%   |
| SanDisk                          | 22        | 5.33%   |
| Micron Technology                | 8         | 1.94%   |
| SK hynix                         | 6         | 1.45%   |
| Phison Electronics               | 6         | 1.45%   |
| Toshiba                          | 5         | 1.21%   |
| Transcend                        | 3         | 0.73%   |
| KIOXIA                           | 3         | 0.73%   |
| Silicon Motion                   | 2         | 0.48%   |
| Nvidia                           | 2         | 0.48%   |
| Lenovo                           | 2         | 0.48%   |
| Kingston Technology Company      | 2         | 0.48%   |
| JMicron Technology               | 2         | 0.48%   |
| Union Memory (Shenzhen)          | 1         | 0.24%   |
| Solid State Storage Technology   | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Realtek Semiconductor            | 1         | 0.24%   |
| Micron/Crucial Technology        | 1         | 0.24%   |
| Lite-On Technology               | 1         | 0.24%   |
| ADATA Technology                 | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 42        | 9.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 39        | 8.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 32        | 7.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 25        | 5.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 20        | 4.45%   |
| Unknown                                                                        | 17        | 3.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 3.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 14        | 3.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 3.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 13        | 2.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 12        | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 2.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 10        | 2.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 8         | 1.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 1.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.11%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.89%   |
| Toshiba XG5 NVMe SSD Controller                                                | 3         | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.67%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 0.67%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.67%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.67%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 3         | 0.67%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 3         | 0.67%   |
| AMD FCH IDE Controller                                                         | 3         | 0.67%   |
| SK hynix hynix unknown                                                         | 2         | 0.45%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.45%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 279       | 65.34%  |
| NVMe | 90        | 21.08%  |
| IDE  | 45        | 10.54%  |
| RAID | 13        | 3.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 306       | 82.26%  |
| AMD    | 65        | 17.47%  |
| ARM    | 1         | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz        | 13        | 3.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 8         | 2.12%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 7         | 1.86%   |
| Intel Core 2 Duo                         | 7         | 1.86%   |
| AMD EPYC 3201 8-Core Processor           | 7         | 1.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 1.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 5         | 1.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 5         | 1.33%   |
| Intel Core i3-3227U CPU @ 1.90GHz        | 5         | 1.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 5         | 1.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 5         | 1.33%   |
| Intel CPU Version                        | 4         | 1.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 4         | 1.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 4         | 1.06%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 4         | 1.06%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 4         | 1.06%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 4         | 1.06%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz     | 4         | 1.06%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 4         | 1.06%   |
| AMD EPYC 3101 4-Core Processor           | 4         | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 3         | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz        | 3         | 0.8%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 3         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz        | 3         | 0.8%    |
| Intel Core i7-4600U CPU @ 2.10GHz        | 3         | 0.8%    |
| Intel Core i7-2760QM CPU @ 2.40GHz       | 3         | 0.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 3         | 0.8%    |
| Intel Core i5-6440HQ CPU @ 2.60GHz       | 3         | 0.8%    |
| Intel Core i5-4300M CPU @ 2.60GHz        | 3         | 0.8%    |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 3         | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 3         | 0.8%    |
| Intel Celeron CPU N3450 @ 1.10GHz        | 3         | 0.8%    |
| AMD Ryzen Embedded V1500B                | 3         | 0.8%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 2         | 0.53%   |
| Intel Pentium M processor                | 2         | 0.53%   |
| Intel Pentium 4                          | 2         | 0.53%   |
| Intel Genuine CPU                        | 2         | 0.53%   |
| Intel Core i9-8950HK CPU @ 2.90GHz       | 2         | 0.53%   |
| Intel Core i7-8850H CPU @ 2.60GHz        | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 106       | 28.34%  |
| Intel Core i7          | 94        | 25.13%  |
| Other                  | 26        | 6.95%   |
| Intel Core 2 Duo       | 22        | 5.88%   |
| Intel Core i3          | 19        | 5.08%   |
| Intel Celeron          | 13        | 3.48%   |
| AMD EPYC               | 11        | 2.94%   |
| AMD Ryzen 7            | 9         | 2.41%   |
| AMD Ryzen 5            | 6         | 1.6%    |
| Intel Core 2           | 5         | 1.34%   |
| Intel Atom             | 5         | 1.34%   |
| Intel Core i9          | 4         | 1.07%   |
| AMD Ryzen 5 PRO        | 4         | 1.07%   |
| Intel Pentium M        | 3         | 0.8%    |
| Intel Pentium          | 3         | 0.8%    |
| AMD Ryzen Embedded     | 3         | 0.8%    |
| AMD Ryzen 7 PRO        | 3         | 0.8%    |
| AMD Ryzen 3            | 3         | 0.8%    |
| AMD A10                | 3         | 0.8%    |
| Intel Xeon             | 2         | 0.53%   |
| Intel Pentium Silver   | 2         | 0.53%   |
| Intel Pentium 4        | 2         | 0.53%   |
| Intel Genuine          | 2         | 0.53%   |
| AMD GX                 | 2         | 0.53%   |
| AMD E                  | 2         | 0.53%   |
| AMD C-50               | 2         | 0.53%   |
| AMD A8                 | 2         | 0.53%   |
| AMD A6                 | 2         | 0.53%   |
| Intel Pentium Dual     | 1         | 0.27%   |
| Intel Mobile Pentium 4 | 1         | 0.27%   |
| Intel Mobile Celeron   | 1         | 0.27%   |
| Intel Core m3          | 1         | 0.27%   |
| Intel Core 2 Extreme   | 1         | 0.27%   |
| ARM Cortex             | 1         | 0.27%   |
| AMD Ryzen 9            | 1         | 0.27%   |
| AMD Phenom II          | 1         | 0.27%   |
| AMD E2                 | 1         | 0.27%   |
| AMD E1                 | 1         | 0.27%   |
| AMD C-60               | 1         | 0.27%   |
| AMD Athlon X2          | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 173       | 46.26%  |
| 4       | 109       | 29.14%  |
| 8       | 28        | 7.49%   |
| Unknown | 28        | 7.49%   |
| 6       | 13        | 3.48%   |
| 1       | 9         | 2.41%   |
| 16      | 8         | 2.14%   |
| 12      | 5         | 1.34%   |
| 20      | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 361       | 97.04%  |
| Unknown | 7         | 1.88%   |
| 2       | 4         | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 242       | 64.71%  |
| 1       | 99        | 26.47%  |
| Unknown | 33        | 8.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 60        | 16.13%  |
| IvyBridge       | 39        | 10.48%  |
| SandyBridge     | 37        | 9.95%   |
| Haswell         | 29        | 7.8%    |
| Skylake         | 23        | 6.18%   |
| Westmere        | 19        | 5.11%   |
| Broadwell       | 18        | 4.84%   |
| Zen             | 16        | 4.3%    |
| Core            | 16        | 4.3%    |
| Penryn          | 13        | 3.49%   |
| Zen 2           | 11        | 2.96%   |
| Zen+            | 10        | 2.69%   |
| TigerLake       | 10        | 2.69%   |
| Bonnell         | 8         | 2.15%   |
| Unknown         | 8         | 2.15%   |
| Bobcat          | 7         | 1.88%   |
| Silvermont      | 5         | 1.34%   |
| Goldmont plus   | 5         | 1.34%   |
| CometLake       | 5         | 1.34%   |
| Goldmont        | 4         | 1.08%   |
| Excavator       | 4         | 1.08%   |
| Puma            | 3         | 0.81%   |
| P6              | 3         | 0.81%   |
| NetBurst        | 3         | 0.81%   |
| IceLake         | 3         | 0.81%   |
| Nehalem         | 2         | 0.54%   |
| K10 Llano       | 2         | 0.54%   |
| K10             | 2         | 0.54%   |
| Jaguar          | 2         | 0.54%   |
| Zen 3           | 1         | 0.27%   |
| Steamroller     | 1         | 0.27%   |
| Piledriver      | 1         | 0.27%   |
| K8 Hammer       | 1         | 0.27%   |
| K8 & K10 hybrid | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 273       | 65.94%  |
| AMD                              | 71        | 17.15%  |
| Nvidia                           | 69        | 16.67%  |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 37        | 8.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 35        | 8.05%   |
| Intel Core Processor Integrated Graphics Controller                           | 17        | 3.91%   |
| Intel HD Graphics 5500                                                        | 16        | 3.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 14        | 3.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 14        | 3.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 13        | 2.99%   |
| Intel HD Graphics 620                                                         | 11        | 2.53%   |
| Intel UHD Graphics 620                                                        | 10        | 2.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 10        | 2.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 2.3%    |
| AMD Renoir                                                                    | 10        | 2.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 10        | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 9         | 2.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 9         | 2.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 1.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 8         | 1.84%   |
| Intel HD Graphics 530                                                         | 8         | 1.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 8         | 1.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 7         | 1.61%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 6         | 1.38%   |
| Intel HD Graphics 630                                                         | 6         | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 5         | 1.15%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 4         | 0.92%   |
| Nvidia G86M [Quadro NVS 140M]                                                 | 4         | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 0.69%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 3         | 0.69%   |
| Intel HD Graphics 500                                                         | 3         | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 0.69%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                         | 3         | 0.69%   |
| Nvidia TU117M                                                                 | 2         | 0.46%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 2         | 0.46%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 2         | 0.46%   |
| Nvidia GT218M [NVS 3100M]                                                     | 2         | 0.46%   |
| Nvidia GP108M [GeForce MX150]                                                 | 2         | 0.46%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 2         | 0.46%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.46%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                   | 2         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 196       | 52.69%  |
| 1 x AMD        | 54        | 14.52%  |
| Intel + Nvidia | 42        | 11.29%  |
| 2 x Intel      | 26        | 6.99%   |
| 1 x Nvidia     | 22        | 5.91%   |
| Other          | 14        | 3.76%   |
| Intel + AMD    | 9         | 2.42%   |
| AMD + Nvidia   | 5         | 1.34%   |
| 2 x AMD        | 3         | 0.81%   |
| 1 x SiS        | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 320       | 86.25%  |
| Proprietary | 26        | 7.01%   |
| Unknown     | 25        | 6.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 322       | 85.41%  |
| 0.01-0.5   | 22        | 5.84%   |
| 1.01-2.0   | 15        | 3.98%   |
| 3.01-4.0   | 7         | 1.86%   |
| 0.51-1.0   | 6         | 1.59%   |
| 5.01-6.0   | 3         | 0.8%    |
| 7.01-8.0   | 1         | 0.27%   |
| 2.01-3.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 58        | 20.35%  |
| AU Optronics            | 50        | 17.54%  |
| BOE                     | 39        | 13.68%  |
| Samsung Electronics     | 29        | 10.18%  |
| Chimei Innolux          | 26        | 9.12%   |
| Lenovo                  | 18        | 6.32%   |
| Apple                   | 9         | 3.16%   |
| Sharp                   | 7         | 2.46%   |
| Chi Mei Optoelectronics | 7         | 2.46%   |
| Sceptre Tech            | 4         | 1.4%    |
| LGD                     | 3         | 1.05%   |
| InfoVision              | 3         | 1.05%   |
| Dell                    | 3         | 1.05%   |
| Ancor Communications    | 3         | 1.05%   |
| Vizio                   | 2         | 0.7%    |
| IBM                     | 2         | 0.7%    |
| Hewlett-Packard         | 2         | 0.7%    |
| HannStar                | 2         | 0.7%    |
| BenQ                    | 2         | 0.7%    |
| Acer                    | 2         | 0.7%    |
| Toshiba                 | 1         | 0.35%   |
| Tech Concepts           | 1         | 0.35%   |
| PANDA                   | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| LG Philips              | 1         | 0.35%   |
| LG Electronics          | 1         | 0.35%   |
| Lenovo Group Limited    | 1         | 0.35%   |
| HJW                     | 1         | 0.35%   |
| Goldstar                | 1         | 0.35%   |
| CTO                     | 1         | 0.35%   |
| ASUSTek Computer        | 1         | 0.35%   |
| Aosiman                 | 1         | 0.35%   |
| AOC                     | 1         | 0.35%   |
| AGO                     | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 6         | 2.1%    |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 6         | 2.1%    |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 5         | 1.75%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch     | 4         | 1.4%    |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch           | 3         | 1.05%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 3         | 1.05%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 3         | 1.05%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 3         | 1.05%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 3         | 1.05%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 3         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 3         | 1.05%   |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                     | 3         | 1.05%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 2         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch     | 2         | 0.7%    |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 2         | 0.7%    |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 2         | 0.7%    |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch             | 2         | 0.7%    |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch             | 2         | 0.7%    |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch              | 2         | 0.7%    |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch              | 2         | 0.7%    |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 2         | 0.7%    |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 2         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 2         | 0.7%    |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                     | 2         | 0.7%    |
| BOE LCD Monitor BOE06CB 1920x1080 340x190mm 15.3-inch                    | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO24ED 1920x1080 340x190mm 15.3-inch           | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 0.7%    |
| Apple LCD Monitor APP9CC5 1280x800 290x180mm 13.4-inch                   | 2         | 0.7%    |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                   | 2         | 0.7%    |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 600x340mm 27.2-inch    | 2         | 0.7%    |
| Vizio M260VA VIZ0067 1360x768 580x320mm 26.1-inch                        | 1         | 0.35%   |
| Vizio E65-F1 VIZ1035 3840x2160 1430x800mm 64.5-inch                      | 1         | 0.35%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                         | 1         | 0.35%   |
| Tech Concepts LCD Monitor 43S435                                         | 1         | 0.35%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 340x190mm 15.3-inch                  | 1         | 0.35%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 290x180mm 13.4-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP148E 1920x1080 340x190mm 15.3-inch                  | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 98        | 35.13%  |
| 1920x1080 (FHD)    | 86        | 30.82%  |
| 1600x900 (HD+)     | 21        | 7.53%   |
| 1280x800 (WXGA)    | 20        | 7.17%   |
| 2560x1440 (QHD)    | 10        | 3.58%   |
| 3840x2160 (4K)     | 8         | 2.87%   |
| 2256x1504          | 6         | 2.15%   |
| 2560x1080          | 4         | 1.43%   |
| 1440x900 (WXGA+)   | 4         | 1.43%   |
| 1024x600           | 4         | 1.43%   |
| 3440x1440          | 2         | 0.72%   |
| 2560x1600          | 2         | 0.72%   |
| 1680x1050 (WSXGA+) | 2         | 0.72%   |
| Unknown            | 2         | 0.72%   |
| 5760x2160          | 1         | 0.36%   |
| 4480x1080          | 1         | 0.36%   |
| 3840x1600          | 1         | 0.36%   |
| 3200x1800 (QHD+)   | 1         | 0.36%   |
| 2880x1620          | 1         | 0.36%   |
| 1920x1200 (WUXGA)  | 1         | 0.36%   |
| 1400x1050          | 1         | 0.36%   |
| 1360x768           | 1         | 0.36%   |
| 1280x1024 (SXGA)   | 1         | 0.36%   |
| 1024x768 (XGA)     | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 98        | 34.75%  |
| 13      | 83        | 29.43%  |
| 12      | 25        | 8.87%   |
| 17      | 15        | 5.32%   |
| 14      | 13        | 4.61%   |
| 11      | 10        | 3.55%   |
| 27      | 8         | 2.84%   |
| Unknown | 6         | 2.13%   |
| 24      | 5         | 1.77%   |
| 29      | 3         | 1.06%   |
| 64      | 2         | 0.71%   |
| 34      | 2         | 0.71%   |
| 23      | 2         | 0.71%   |
| 10      | 2         | 0.71%   |
| 37      | 1         | 0.35%   |
| 35      | 1         | 0.35%   |
| 31      | 1         | 0.35%   |
| 26      | 1         | 0.35%   |
| 19      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |
| 9       | 1         | 0.35%   |
| 8       | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 156       | 55.52%  |
| 201-300     | 76        | 27.05%  |
| 351-400     | 15        | 5.34%   |
| 501-600     | 14        | 4.98%   |
| Unknown     | 6         | 2.14%   |
| 601-700     | 5         | 1.78%   |
| 801-900     | 2         | 0.71%   |
| 701-800     | 2         | 0.71%   |
| 101-200     | 2         | 0.71%   |
| 1001-1500   | 2         | 0.71%   |
| 401-500     | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 210       | 78.95%  |
| 16/10   | 30        | 11.28%  |
| 3/2     | 9         | 3.38%   |
| 21/9    | 7         | 2.63%   |
| Unknown | 5         | 1.88%   |
| 4/3     | 3         | 1.13%   |
| 6/5     | 1         | 0.38%   |
| 5/4     | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 85        | 30.04%  |
| 91-100         | 77        | 27.21%  |
| 61-70          | 26        | 9.19%   |
| 101-110        | 23        | 8.13%   |
| 121-130        | 13        | 4.59%   |
| 301-350        | 11        | 3.89%   |
| 71-80          | 9         | 3.18%   |
| 51-60          | 9         | 3.18%   |
| 201-250        | 7         | 2.47%   |
| Unknown        | 6         | 2.12%   |
| 351-500        | 4         | 1.41%   |
| More than 1000 | 2         | 0.71%   |
| 41-50          | 2         | 0.71%   |
| 1-40           | 2         | 0.71%   |
| 131-140        | 2         | 0.71%   |
| 251-300        | 1         | 0.35%   |
| 151-200        | 1         | 0.35%   |
| 141-150        | 1         | 0.35%   |
| 111-120        | 1         | 0.35%   |
| 501-1000       | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 121       | 43.06%  |
| 101-120       | 93        | 33.1%   |
| 51-100        | 30        | 10.68%  |
| 161-240       | 25        | 8.9%    |
| More than 240 | 6         | 2.14%   |
| Unknown       | 6         | 2.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 244       | 64.72%  |
| 0     | 104       | 27.59%  |
| 2     | 27        | 7.16%   |
| 4     | 1         | 0.27%   |
| 3     | 1         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 262       | 46.7%   |
| Realtek Semiconductor            | 134       | 23.89%  |
| Qualcomm Atheros                 | 57        | 10.16%  |
| Broadcom                         | 48        | 8.56%   |
| AMD                              | 14        | 2.5%    |
| Edimax Technology                | 8         | 1.43%   |
| TP-Link                          | 5         | 0.89%   |
| Marvell Technology Group         | 5         | 0.89%   |
| Ralink Technology                | 3         | 0.53%   |
| Ralink                           | 3         | 0.53%   |
| NetGear                          | 3         | 0.53%   |
| Nvidia                           | 2         | 0.36%   |
| Novatel Wireless                 | 2         | 0.36%   |
| MediaTek                         | 2         | 0.36%   |
| Google                           | 2         | 0.36%   |
| ASUSTek Computer                 | 2         | 0.36%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Sierra Wireless                  | 1         | 0.18%   |
| Samsung Electronics              | 1         | 0.18%   |
| Qualcomm                         | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.18%   |
| Lenovo                           | 1         | 0.18%   |
| dog hunter                       | 1         | 0.18%   |
| D-Link System                    | 1         | 0.18%   |
| D-Link                           | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 11.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 5.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 32        | 4.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 4.2%    |
| Intel Wireless 7260                                               | 22        | 2.98%   |
| Intel Wireless 8265 / 8275                                        | 20        | 2.71%   |
| Intel Wireless 8260                                               | 19        | 2.57%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 2.3%    |
| Intel Wireless 7265                                               | 16        | 2.17%   |
| Intel I210 Gigabit Network Connection                             | 14        | 1.9%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 14        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 9         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 1.22%   |
| Intel Wireless-AC 9260                                            | 9         | 1.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 1.22%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8         | 1.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 8         | 1.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 8         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 0.95%   |
| Intel Wireless 3165                                               | 7         | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.95%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 7         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 6         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.81%   |
| Intel 82566MM Gigabit Network Connection                          | 6         | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.68%   |
| Intel Wireless 3160                                               | 5         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 5         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 225       | 59.06%  |
| Qualcomm Atheros      | 49        | 12.86%  |
| Realtek Semiconductor | 42        | 11.02%  |
| Broadcom              | 37        | 9.71%   |
| Edimax Technology     | 8         | 2.1%    |
| TP-Link               | 5         | 1.31%   |
| Ralink Technology     | 3         | 0.79%   |
| Ralink                | 3         | 0.79%   |
| NetGear               | 3         | 0.79%   |
| ASUSTek Computer      | 2         | 0.52%   |
| Sierra Wireless       | 1         | 0.26%   |
| MediaTek              | 1         | 0.26%   |
| D-Link System         | 1         | 0.26%   |
| D-Link                | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 8.33%   |
| Intel Wireless 7260                                                     | 22        | 5.73%   |
| Intel Wireless 8265 / 8275                                              | 20        | 5.21%   |
| Intel Wireless 8260                                                     | 19        | 4.95%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 4.43%   |
| Intel Wireless 7265                                                     | 16        | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.34%   |
| Intel Wireless-AC 9260                                                  | 9         | 2.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 2.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 8         | 2.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 8         | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.82%   |
| Intel Wireless 3165                                                     | 7         | 1.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.3%    |
| Intel Wireless 3160                                                     | 5         | 1.3%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 5         | 1.3%    |
| Intel Centrino Advanced-N 6200                                          | 5         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.04%   |
| Intel WiFi Link 5100                                                    | 4         | 1.04%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.04%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 153       | 44.61%  |
| Realtek Semiconductor            | 117       | 34.11%  |
| Broadcom                         | 29        | 8.45%   |
| Qualcomm Atheros                 | 14        | 4.08%   |
| AMD                              | 14        | 4.08%   |
| Marvell Technology Group         | 5         | 1.46%   |
| Nvidia                           | 2         | 0.58%   |
| Novatel Wireless                 | 2         | 0.58%   |
| Google                           | 2         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Samsung Electronics              | 1         | 0.29%   |
| Qualcomm                         | 1         | 0.29%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.29%   |
| Lenovo                           | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 23.99%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 12.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 8.96%   |
| Intel I210 Gigabit Network Connection                             | 14        | 4.05%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 14        | 4.05%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 2.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 2.6%    |
| Intel 82577LM Gigabit Network Connection                          | 9         | 2.6%    |
| Intel Ethernet Connection I219-LM                                 | 7         | 2.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 2.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 1.73%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 1.73%   |
| Intel 82566MM Gigabit Network Connection                          | 6         | 1.73%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.16%   |
| Intel Ethernet Connection I219-V                                  | 4         | 1.16%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.16%   |
| Intel 82573L Gigabit Ethernet Controller                          | 3         | 0.87%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.87%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.87%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 3         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.58%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.58%   |
| Novatel Wireless MiFi 8800L RNDIS Control RNDIS Ethernet Data     | 2         | 0.58%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.58%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.58%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.58%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.58%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.58%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 2         | 0.58%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.58%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 347       | 51.33%  |
| Ethernet | 321       | 47.49%  |
| Modem    | 7         | 1.04%   |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 266       | 51.85%  |
| Ethernet | 247       | 48.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 284       | 76.34%  |
| 1     | 58        | 15.59%  |
| 3     | 13        | 3.49%   |
| 6     | 11        | 2.96%   |
| 5     | 3         | 0.81%   |
| 0     | 3         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 339       | 89.68%  |
| Yes  | 39        | 10.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 134       | 55.6%   |
| Broadcom                        | 33        | 13.69%  |
| Apple                           | 20        | 8.3%    |
| Realtek Semiconductor           | 14        | 5.81%   |
| Qualcomm Atheros Communications | 12        | 4.98%   |
| IMC Networks                    | 10        | 4.15%   |
| Dell                            | 8         | 3.32%   |
| Foxconn / Hon Hai               | 4         | 1.66%   |
| Alps Electric                   | 2         | 0.83%   |
| Realtek                         | 1         | 0.41%   |
| Lite-On Technology              | 1         | 0.41%   |
| Hewlett-Packard                 | 1         | 0.41%   |
| ASUSTek Computer                | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 68        | 28.1%   |
| Intel AX200 Bluetooth                                       | 16        | 6.61%   |
| Intel AX201 Bluetooth                                       | 15        | 6.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 14        | 5.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 14        | 5.79%   |
| Apple Bluetooth Host Controller                             | 12        | 4.96%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 10        | 4.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 7         | 2.89%   |
| Realtek  Bluetooth 4.2 Adapter                              | 6         | 2.48%   |
| Intel AX210 Bluetooth                                       | 6         | 2.48%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 1.65%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 4         | 1.65%   |
| Dell DW375 Bluetooth Module                                 | 4         | 1.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 1.65%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 1.24%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 3         | 1.24%   |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 1.24%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 3         | 1.24%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.83%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 0.83%   |
| Realtek Bluetooth Radio                                     | 2         | 0.83%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 0.83%   |
| IMC Networks Wireless_Device                                | 2         | 0.83%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 0.83%   |
| IMC Networks Bluetooth module                               | 2         | 0.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 0.83%   |
| Alps Electric BCM2046 Bluetooth Device                      | 2         | 0.83%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.41%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.41%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 0.41%   |
| Realtek Bluetooth Radio                                     | 1         | 0.41%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1                     | 1         | 0.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.41%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.41%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.41%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 0.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.41%   |
| Intel Intel Wireless Bluetooth                              | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 300       | 70.42%  |
| AMD                              | 76        | 17.84%  |
| Nvidia                           | 35        | 8.22%   |
| Realtek Semiconductor            | 3         | 0.7%    |
| C-Media Electronics              | 3         | 0.7%    |
| Texas Instruments                | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Logitech                         | 1         | 0.23%   |
| Lenovo                           | 1         | 0.23%   |
| JMTek                            | 1         | 0.23%   |
| ESS Technology                   | 1         | 0.23%   |
| CMX Systems                      | 1         | 0.23%   |
| Cambridge Silicon Radio          | 1         | 0.23%   |
| Blue Microphones                 | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 41        | 7.99%   |
| Intel Sunrise Point-LP HD Audio                                            | 36        | 7.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 35        | 6.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 28        | 5.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 4.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 3.51%   |
| Intel Broadwell-U Audio Controller                                         | 18        | 3.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 3.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 2.92%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 2.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 14        | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 2.53%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 2.53%   |
| AMD FCH Azalia Controller                                                  | 12        | 2.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11        | 2.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 1.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 1.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.17%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.97%   |
| AMD Wrestler HDMI Audio                                                    | 5         | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.78%   |
| Nvidia GT216 HDMI Audio Controller                                         | 4         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.58%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.58%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 116       | 28.86%  |
| SK hynix            | 92        | 22.89%  |
| Micron Technology   | 40        | 9.95%   |
| Crucial             | 30        | 7.46%   |
| Unknown             | 26        | 6.47%   |
| Kingston            | 17        | 4.23%   |
| Transcend           | 15        | 3.73%   |
| Elpida              | 11        | 2.74%   |
| Nanya Technology    | 7         | 1.74%   |
| G.Skill             | 7         | 1.74%   |
| Ramaxel Technology  | 6         | 1.49%   |
| Unknown             | 6         | 1.49%   |
| PNY                 | 5         | 1.24%   |
| Team                | 3         | 0.75%   |
| Goldkey             | 3         | 0.75%   |
| Avant               | 3         | 0.75%   |
| Unknown (ABCD)      | 2         | 0.5%    |
| A-DATA Technology   | 2         | 0.5%    |
| Super Talent        | 1         | 0.25%   |
| Silicon Power       | 1         | 0.25%   |
| Sesame              | 1         | 0.25%   |
| PKI/Kingston        | 1         | 0.25%   |
| Patriot             | 1         | 0.25%   |
| Neo Forza           | 1         | 0.25%   |
| Golden Empire       | 1         | 0.25%   |
| Gold Key            | 1         | 0.25%   |
| Corsair             | 1         | 0.25%   |
| Apacer              | 1         | 0.25%   |
| 09490000802C        | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 2.05%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.83%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 1.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.83%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 1.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 1.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s            | 6         | 1.37%   |
| Unknown                                                          | 6         | 1.37%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s              | 5         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.14%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.91%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 0.91%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 4         | 0.91%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 4         | 0.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.91%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.91%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.91%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                       | 3         | 0.68%   |
| Transcend RAM TS1GLH64V6B 8GB SODIMM DDR4 1333MT/s               | 3         | 0.68%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 3         | 0.68%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 3         | 0.68%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 3         | 0.68%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.68%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 3         | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 3         | 0.68%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 3         | 0.68%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.68%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.68%   |
| Unknown RAM PartNum 0 512MB Chip DDR2 533MT/s                    | 2         | 0.46%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 2         | 0.46%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 165       | 49.4%   |
| DDR4    | 120       | 35.93%  |
| DDR2    | 25        | 7.49%   |
| LPDDR3  | 7         | 2.1%    |
| DDR     | 6         | 1.8%    |
| LPDDR4  | 5         | 1.5%    |
| LPDDR5  | 2         | 0.6%    |
| Unknown | 2         | 0.6%    |
| SRAM    | 1         | 0.3%    |
| SDRAM   | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 315       | 93.75%  |
| Row Of Chips | 12        | 3.57%   |
| Chip         | 7         | 2.08%   |
| Unknown      | 2         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 135       | 35.53%  |
| 4096  | 125       | 32.89%  |
| 2048  | 56        | 14.74%  |
| 16384 | 33        | 8.68%   |
| 1024  | 17        | 4.47%   |
| 32768 | 12        | 3.16%   |
| 512   | 1         | 0.26%   |
| 256   | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 99        | 26.4%   |
| 2667    | 49        | 13.07%  |
| 1333    | 47        | 12.53%  |
| 2400    | 30        | 8%      |
| 3200    | 29        | 7.73%   |
| 1334    | 26        | 6.93%   |
| 2133    | 25        | 6.67%   |
| 667     | 16        | 4.27%   |
| 1067    | 10        | 2.67%   |
| 1867    | 9         | 2.4%    |
| 800     | 8         | 2.13%   |
| Unknown | 7         | 1.87%   |
| 975     | 4         | 1.07%   |
| 533     | 4         | 1.07%   |
| 4267    | 3         | 0.8%    |
| 1200    | 2         | 0.53%   |
| 6400    | 1         | 0.27%   |
| 4800    | 1         | 0.27%   |
| 4266    | 1         | 0.27%   |
| 1866    | 1         | 0.27%   |
| 1066    | 1         | 0.27%   |
| 200     | 1         | 0.27%   |
| 166     | 1         | 0.27%   |

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
| Chicony Electronics                    | 72        | 29.03%  |
| Acer                                   | 26        | 10.48%  |
| Realtek Semiconductor                  | 21        | 8.47%   |
| Microdia                               | 21        | 8.47%   |
| IMC Networks                           | 20        | 8.06%   |
| Sunplus Innovation Technology          | 17        | 6.85%   |
| Apple                                  | 10        | 4.03%   |
| Suyin                                  | 8         | 3.23%   |
| Lite-On Technology                     | 8         | 3.23%   |
| Quanta                                 | 7         | 2.82%   |
| Luxvisions Innotech Limited            | 7         | 2.82%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.82%   |
| Lenovo                                 | 4         | 1.61%   |
| Syntek                                 | 3         | 1.21%   |
| Importek                               | 3         | 1.21%   |
| Ricoh                                  | 2         | 0.81%   |
| Primax Electronics                     | 2         | 0.81%   |
| OmniVision Technologies                | 2         | 0.81%   |
| Logitech                               | 2         | 0.81%   |
| Alcor Micro                            | 2         | 0.81%   |
| Unknown                                | 1         | 0.4%    |
| Silicon Motion                         | 1         | 0.4%    |
| Intel                                  | 1         | 0.4%    |
| ALi                                    | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 25        | 10.04%  |
| Acer Integrated Camera                               | 15        | 6.02%   |
| Microdia Integrated Webcam                           | 8         | 3.21%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 8         | 3.21%   |
| Realtek Integrated_Webcam_HD                         | 7         | 2.81%   |
| Apple FaceTime HD Camera                             | 7         | 2.81%   |
| Sunplus Integrated_Webcam_HD                         | 6         | 2.41%   |
| Lite-On Integrated Camera                            | 6         | 2.41%   |
| Chicony Integrated Camera [ThinkPad]                 | 6         | 2.41%   |
| Realtek Realtek USB2.0 PC Camera                     | 5         | 2.01%   |
| IMC Networks Integrated Camera                       | 5         | 2.01%   |
| Chicony Integrated Camera (1280x720@30)              | 5         | 2.01%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 4         | 1.61%   |
| Microdia Dell Laptop Integrated Webcam HD            | 4         | 1.61%   |
| Lenovo Integrated Webcam [R5U877]                    | 4         | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 1.61%   |
| Acer ThinkPad Integrated Camera                      | 4         | 1.61%   |
| Suyin Integrated_Webcam_HD                           | 3         | 1.2%    |
| Sunplus HD WebCam                                    | 3         | 1.2%    |
| Quanta HP Webcam                                     | 3         | 1.2%    |
| Quanta HP TrueVision HD Camera                       | 3         | 1.2%    |
| Luxvisions Innotech Limited Integrated Camera        | 3         | 1.2%    |
| IMC Networks UVC VGA Webcam                          | 3         | 1.2%    |
| Chicony HD Webcam                                    | 3         | 1.2%    |
| Chicony Chicony USB2.0 Camera                        | 3         | 1.2%    |
| Syntek Lenovo EasyCamera                             | 2         | 0.8%    |
| Sunplus Dell E5570 integrated webcam                 | 2         | 0.8%    |
| Realtek Laptop Camera                                | 2         | 0.8%    |
| Realtek Integrated Webcam HD                         | 2         | 0.8%    |
| Realtek Integrated Webcam                            | 2         | 0.8%    |
| Primax HP HD Webcam [Fixed]                          | 2         | 0.8%    |
| OmniVision OV2640 Webcam                             | 2         | 0.8%    |
| Microdia Integrated_Webcam_HD                        | 2         | 0.8%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.8%    |
| IMC Networks USB2.0 UVC HD Webcam                    | 2         | 0.8%    |
| IMC Networks EasyCamera                              | 2         | 0.8%    |
| Chicony VGA WebCam                                   | 2         | 0.8%    |
| Chicony thinkpad t430s camera                        | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 37.68%  |
| Upek                       | 11        | 15.94%  |
| Synaptics                  | 10        | 14.49%  |
| STMicroelectronics         | 10        | 14.49%  |
| Shenzhen Goodix Technology | 5         | 7.25%   |
| AuthenTec                  | 4         | 5.8%    |
| Samsung Electronics        | 1         | 1.45%   |
| Focal-systems.Corp         | 1         | 1.45%   |
| Broadcom                   | 1         | 1.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 13        | 18.84%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 11        | 15.94%  |
| STMicroelectronics Fingerprint Reader                                        | 10        | 14.49%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 7.25%   |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 7.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 4         | 5.8%    |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 4.35%   |
| Validity Sensors Synaptics WBDI                                              | 3         | 4.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 2.9%    |
| AuthenTec AuthenTec Inc. AES1660                                             | 2         | 2.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.45%   |
| Validity Sensors VFS491                                                      | 1         | 1.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 1.45%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.45%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 1.45%   |
| Synaptics product 0x00be                                                     | 1         | 1.45%   |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 1.45%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 1.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.45%   |
| AuthenTec AES2810                                                            | 1         | 1.45%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.45%   |

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
| 2     | 118       | 30.26%  |
| 1     | 113       | 28.97%  |
| 3     | 67        | 17.18%  |
| 0     | 56        | 14.36%  |
| 4     | 26        | 6.67%   |
| 5     | 7         | 1.79%   |
| 6     | 3         | 0.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 255       | 41.53%  |
| Bluetooth                | 92        | 14.98%  |
| Net/wireless             | 71        | 11.56%  |
| Card reader              | 67        | 10.91%  |
| Fingerprint reader       | 57        | 9.28%   |
| Firewire controller      | 29        | 4.72%   |
| Sound                    | 10        | 1.63%   |
| Storage                  | 9         | 1.47%   |
| Graphics card            | 7         | 1.14%   |
| Modem                    | 6         | 0.98%   |
| Network                  | 5         | 0.81%   |
| Storage/ata              | 2         | 0.33%   |
| Net/ethernet             | 2         | 0.33%   |
| Storage/ide              | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |

