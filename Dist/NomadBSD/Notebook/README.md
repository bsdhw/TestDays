NomadBSD - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for NomadBSD.

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

Total: 131

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | Aspire 7738                 | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| Lenovo        | G50-70 20351                | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple         | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [91a1870b65](https://bsd-hardware.info/?probe=91a1870b65) | Sep 01, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [995a8a5e6f](https://bsd-hardware.info/?probe=995a8a5e6f) | Jul 16, 2022 |
| Lenovo        | V580 20147                  | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| HP            | 255 G8 Notebook PC          | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| Dell          | Latitude 5290               | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HP            | ProBook 450 G2              | [c4f7b8a774](https://bsd-hardware.info/?probe=c4f7b8a774) | Apr 22, 2022 |
| Dell          | Studio 1555                 | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| ASUSTek       | M51Sr                       | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [2af47b6502](https://bsd-hardware.info/?probe=2af47b6502) | Mar 03, 2022 |
| Dell          | Latitude D630               | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | [e27a6f46fc](https://bsd-hardware.info/?probe=e27a6f46fc) | Feb 26, 2022 |
| HP            | Laptop 15-db0xxx            | [766e62f699](https://bsd-hardware.info/?probe=766e62f699) | Feb 12, 2022 |
| HP            | Notebook                    | [1758596e26](https://bsd-hardware.info/?probe=1758596e26) | Feb 12, 2022 |
| HP            | Pavilion Notebook           | [24f3a7da57](https://bsd-hardware.info/?probe=24f3a7da57) | Feb 07, 2022 |
| ASUSTek       | 1000                        | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Acer          | Aspire 3810T                | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| HP            | ZBook Studio G3             | [767b44a6ae](https://bsd-hardware.info/?probe=767b44a6ae) | Oct 30, 2021 |
| ASUSTek       | X202E                       | [54259ac9a1](https://bsd-hardware.info/?probe=54259ac9a1) | Oct 29, 2021 |
| Sony          | VJS121C11N                  | [d86c621ef0](https://bsd-hardware.info/?probe=d86c621ef0) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [2d72b6939d](https://bsd-hardware.info/?probe=2d72b6939d) | Oct 24, 2021 |
| ASUSTek       | X540YA                      | [c5751c736c](https://bsd-hardware.info/?probe=c5751c736c) | Sep 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [d8f8901ae7](https://bsd-hardware.info/?probe=d8f8901ae7) | Sep 19, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [b00c8e76e8](https://bsd-hardware.info/?probe=b00c8e76e8) | Aug 23, 2021 |
| HP            | Pavilion g6                 | [f1dc5150c2](https://bsd-hardware.info/?probe=f1dc5150c2) | Aug 13, 2021 |
| HP            | 2000                        | [d2240a960b](https://bsd-hardware.info/?probe=d2240a960b) | Aug 05, 2021 |
| HP            | 2000                        | [65d183fe41](https://bsd-hardware.info/?probe=65d183fe41) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [39ef89f214](https://bsd-hardware.info/?probe=39ef89f214) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [4e7ace8a39](https://bsd-hardware.info/?probe=4e7ace8a39) | Aug 04, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [25e208721d](https://bsd-hardware.info/?probe=25e208721d) | Jul 02, 2021 |
| Dell          | Inspiron 15-5568            | [3ed52ae70d](https://bsd-hardware.info/?probe=3ed52ae70d) | Jul 01, 2021 |
| Apple         | MacBookAir6,1               | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| Acer          | Aspire E5-551               | [c9ab1cb207](https://bsd-hardware.info/?probe=c9ab1cb207) | Apr 29, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | [e9155d12c7](https://bsd-hardware.info/?probe=e9155d12c7) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Lenovo        | ThinkPad W541 20EGS04800    | [91d2cd471c](https://bsd-hardware.info/?probe=91d2cd471c) | Apr 16, 2021 |
| Apple         | MacBookPro8,1               | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| HP            | ProBook 640 G1              | [6bc6c5b2bf](https://bsd-hardware.info/?probe=6bc6c5b2bf) | Mar 31, 2021 |
| TUXEDO        | Unknown                     | [35aa6590c6](https://bsd-hardware.info/?probe=35aa6590c6) | Mar 29, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c5e824b558](https://bsd-hardware.info/?probe=c5e824b558) | Mar 29, 2021 |
| Toshiba       | Satellite C660              | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| MSI           | MS-N033                     | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Samsung       | N145P/N250P/N260P           | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Toshiba       | Satellite C660              | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| Notebook      | N650DU                      | [90d705dd1e](https://bsd-hardware.info/?probe=90d705dd1e) | Mar 14, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | [733c5edb74](https://bsd-hardware.info/?probe=733c5edb74) | Mar 08, 2021 |
| HP            | Pavilion dv6000 (RP981EA... | [56844725d1](https://bsd-hardware.info/?probe=56844725d1) | Mar 08, 2021 |
| HP            | Laptop 15-da0xxx            | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [be2ad24d1b](https://bsd-hardware.info/?probe=be2ad24d1b) | Mar 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0e06b5f17f](https://bsd-hardware.info/?probe=0e06b5f17f) | Mar 06, 2021 |
| Dell          | Latitude 5280               | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E754               | [d3d033f879](https://bsd-hardware.info/?probe=d3d033f879) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E736               | [845c584693](https://bsd-hardware.info/?probe=845c584693) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eb7d8c3502](https://bsd-hardware.info/?probe=eb7d8c3502) | Mar 02, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| GEO           | GeoBook3                    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| Clevo         | W55xEU                      | [a66041bae0](https://bsd-hardware.info/?probe=a66041bae0) | Feb 17, 2021 |
| Pegatron      | T12Ah                       | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Clevo         | W55xEU                      | [796ad51947](https://bsd-hardware.info/?probe=796ad51947) | Feb 11, 2021 |
| Clevo         | W55xEU                      | [c28a6397b5](https://bsd-hardware.info/?probe=c28a6397b5) | Feb 11, 2021 |
| Alienware     | M18xR1                      | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| Dell          | Latitude 3410               | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| Dell          | Latitude E4300              | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| Pegatron      | T12Ah                       | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Dell          | Latitude 5400               | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ba45e27f88](https://bsd-hardware.info/?probe=ba45e27f88) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Sony          | VPCM13M1R                   | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| NEC Comput... | PC-GL186Y3AZ                | [b9f8e78467](https://bsd-hardware.info/?probe=b9f8e78467) | Jan 05, 2021 |
| Dell          | Latitude 5280               | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [df9318dcea](https://bsd-hardware.info/?probe=df9318dcea) | Dec 27, 2020 |
| Dell          | Inspiron 5758               | [51ed7b02c2](https://bsd-hardware.info/?probe=51ed7b02c2) | Dec 21, 2020 |
| Acer          | Aspire V5-122               | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Apple         | MacBookPro11,3              | [26f15a2838](https://bsd-hardware.info/?probe=26f15a2838) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [21d88f733e](https://bsd-hardware.info/?probe=21d88f733e) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [cdfcd11f7b](https://bsd-hardware.info/?probe=cdfcd11f7b) | Dec 07, 2020 |
| IBM           | 2647NG8                     | [a0f38de52f](https://bsd-hardware.info/?probe=a0f38de52f) | Nov 22, 2020 |
| HP            | ProBook 640 G1              | [bf763e72ad](https://bsd-hardware.info/?probe=bf763e72ad) | Nov 13, 2020 |
| Acer          | Aspire E5-432               | [39fb05c049](https://bsd-hardware.info/?probe=39fb05c049) | Nov 01, 2020 |
| Acer          | Aspire V3-575G              | [1ff0e90d9d](https://bsd-hardware.info/?probe=1ff0e90d9d) | Oct 24, 2020 |
| Google        | Chell                       | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| Apple         | MacBookAir7,2               | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Dell          | Precision 7530              | [717309ee39](https://bsd-hardware.info/?probe=717309ee39) | Sep 28, 2020 |
| Dell          | Precision 7530              | [6a2635237f](https://bsd-hardware.info/?probe=6a2635237f) | Sep 28, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [f7d13e4696](https://bsd-hardware.info/?probe=f7d13e4696) | Sep 23, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [45f410f4e4](https://bsd-hardware.info/?probe=45f410f4e4) | Sep 23, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| Dell          | Vostro 3750                 | [587a9276bb](https://bsd-hardware.info/?probe=587a9276bb) | Sep 06, 2020 |
| Panasonic     | CF-C1BD06EFG                | [3e876bada1](https://bsd-hardware.info/?probe=3e876bada1) | Sep 02, 2020 |
| Dell          | Inspiron 15-3567            | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| Dell          | Inspiron 5567               | [5ef34cd40f](https://bsd-hardware.info/?probe=5ef34cd40f) | Aug 20, 2020 |
| Acer          | Aspire 5735                 | [6ca9384f34](https://bsd-hardware.info/?probe=6ca9384f34) | Aug 20, 2020 |
| ASUSTek       | X71SL                       | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| HP            | ProBook 640 G1              | [4b7eaf5a6a](https://bsd-hardware.info/?probe=4b7eaf5a6a) | Aug 12, 2020 |
| Dell          | Latitude 5480               | [907e0da9a4](https://bsd-hardware.info/?probe=907e0da9a4) | Aug 08, 2020 |
| HP            | EliteBook 820 G1            | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Google        | Lulu                        | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| Unknown       | Unknown                     | [f9ed1dce06](https://bsd-hardware.info/?probe=f9ed1dce06) | Jul 05, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [b726c4536b](https://bsd-hardware.info/?probe=b726c4536b) | Jul 04, 2020 |
| Dell          | Latitude E7240              | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |
| ASUSTek       | X71SL                       | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| NomadBSD 1.3.2    | 34        | 33.01%  |
| NomadBSD 5806f915 | 32        | 31.07%  |
| NomadBSD 1.4      | 18        | 17.48%  |
| NomadBSD 1.3.1    | 7         | 6.8%    |
| NomadBSD 20221130 | 6         | 5.83%   |
| NomadBSD 1.4-RC1  | 6         | 5.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| NomadBSD | 99        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 92        | 92%     |
| i386  | 8         | 8%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 89        | 89.9%   |
| GNOME   | 6         | 6.06%   |
| KDE5    | 2         | 2.02%   |
| xinitrc | 1         | 1.01%   |
| XFCE    | 1         | 1.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 99        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 93        | 93.94%  |
| SDDM | 6         | 6.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 36        | 36%     |
| Unknown | 16        | 16%     |
| de_DE   | 12        | 12%     |
| en_GB   | 8         | 8%      |
| ru_RU   | 6         | 6%      |
| zh_CN   | 3         | 3%      |
| it_IT   | 3         | 3%      |
| fr_FR   | 3         | 3%      |
| pl_PL   | 2         | 2%      |
| hu_HU   | 2         | 2%      |
| es_ES   | 2         | 2%      |
| tr_TR   | 1         | 1%      |
| lt_LT   | 1         | 1%      |
| ko_KR   | 1         | 1%      |
| fi_FI   | 1         | 1%      |
| en_AU   | 1         | 1%      |
| cs_CZ   | 1         | 1%      |
| bg_BG   | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 94        | 94%     |
| BIOS | 6         | 6%      |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 91        | 91.92%  |
| Zfs  | 8         | 8.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 68        | 68%     |
| MBR  | 32        | 32%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 25        | 25.25%  |
| Dell                | 14        | 14.14%  |
| Hewlett-Packard     | 13        | 13.13%  |
| ASUSTek Computer    | 10        | 10.1%   |
| Acer                | 7         | 7.07%   |
| Apple               | 5         | 5.05%   |
| TUXEDO              | 3         | 3.03%   |
| Sony                | 3         | 3.03%   |
| Samsung Electronics | 2         | 2.02%   |
| Notebook            | 2         | 2.02%   |
| Google              | 2         | 2.02%   |
| Fujitsu             | 2         | 2.02%   |
| Toshiba             | 1         | 1.01%   |
| Pegatron            | 1         | 1.01%   |
| Panasonic           | 1         | 1.01%   |
| NEC Computers       | 1         | 1.01%   |
| MSI                 | 1         | 1.01%   |
| IBM                 | 1         | 1.01%   |
| GEO                 | 1         | 1.01%   |
| Fujitsu Siemens     | 1         | 1.01%   |
| Clevo               | 1         | 1.01%   |
| Alienware           | 1         | 1.01%   |
| Unknown             | 1         | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 2.02%   |
| TUXEDO Pulse 15 Gen2                     | 1         | 1.01%   |
| TUXEDO InfinityBook S 15 Gen6            | 1         | 1.01%   |
| Toshiba Satellite C660                   | 1         | 1.01%   |
| Sony VPCM13M1R                           | 1         | 1.01%   |
| Sony VJS121C11N                          | 1         | 1.01%   |
| Sony SVE1713S1RW                         | 1         | 1.01%   |
| Samsung N145P/N250P/N260P                | 1         | 1.01%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 1.01%   |
| Pegatron T12Ah                           | 1         | 1.01%   |
| Panasonic CF-C1BD06EFG                   | 1         | 1.01%   |
| Notebook W650DC,DD                       | 1         | 1.01%   |
| Notebook N650DU                          | 1         | 1.01%   |
| NEC Computers PC-GL186Y3AZ               | 1         | 1.01%   |
| MSI MS-N033                              | 1         | 1.01%   |
| Lenovo Yoga 710-11IKB 80V6               | 1         | 1.01%   |
| Lenovo V580 20147                        | 1         | 1.01%   |
| Lenovo ThinkPad X201 Tablet 311396U      | 1         | 1.01%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU | 1         | 1.01%   |
| Lenovo ThinkPad W541 20EGS04800          | 1         | 1.01%   |
| Lenovo ThinkPad W520 42844DG             | 1         | 1.01%   |
| Lenovo ThinkPad T530 24295VU             | 1         | 1.01%   |
| Lenovo ThinkPad T510 4384FF3             | 1         | 1.01%   |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 1.01%   |
| Lenovo ThinkPad T490 20RYS06R00          | 1         | 1.01%   |
| Lenovo ThinkPad T480 20L50000GE          | 1         | 1.01%   |
| Lenovo ThinkPad T470s W10DG 20JS001FGE   | 1         | 1.01%   |
| Lenovo ThinkPad T460 20FMS78014          | 1         | 1.01%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 1.01%   |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 1.01%   |
| Lenovo ThinkPad T440p 20AWS0VK00         | 1         | 1.01%   |
| Lenovo ThinkPad T430 2347C32             | 1         | 1.01%   |
| Lenovo ThinkPad S1 Yoga 20C0S0M300       | 1         | 1.01%   |
| Lenovo ThinkPad E14 20RA0036RT           | 1         | 1.01%   |
| Lenovo Legion Y7000 2019 PG0 81T0        | 1         | 1.01%   |
| Lenovo IdeaPad S145-15API 81UT           | 1         | 1.01%   |
| Lenovo IdeaPad 110-15IBR 80T7            | 1         | 1.01%   |
| Lenovo G570 20079                        | 1         | 1.01%   |
| Lenovo G50-70 20351                      | 1         | 1.01%   |
| Lenovo G50-45 80E3                       | 1         | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 17        | 17.17%  |
| Dell Latitude              | 8         | 8.08%   |
| Acer Aspire                | 7         | 7.07%   |
| HP Pavilion                | 3         | 3.03%   |
| Dell Inspiron              | 3         | 3.03%   |
| Lenovo IdeaPad             | 2         | 2.02%   |
| HP ProBook                 | 2         | 2.02%   |
| HP Laptop                  | 2         | 2.02%   |
| Fujitsu LIFEBOOK           | 2         | 2.02%   |
| Unknown                    | 2         | 2.02%   |
| TUXEDO Pulse               | 1         | 1.01%   |
| TUXEDO InfinityBook        | 1         | 1.01%   |
| Toshiba Satellite          | 1         | 1.01%   |
| Sony VPCM13M1R             | 1         | 1.01%   |
| Sony VJS121C11N            | 1         | 1.01%   |
| Sony SVE1713S1RW           | 1         | 1.01%   |
| Samsung N145P              | 1         | 1.01%   |
| Samsung 300E5EV            | 1         | 1.01%   |
| Pegatron T12Ah             | 1         | 1.01%   |
| Panasonic CF-C1BD06EFG     | 1         | 1.01%   |
| Notebook W650DC            | 1         | 1.01%   |
| Notebook N650DU            | 1         | 1.01%   |
| NEC Computers PC-GL186Y3AZ | 1         | 1.01%   |
| MSI MS-N033                | 1         | 1.01%   |
| Lenovo Yoga                | 1         | 1.01%   |
| Lenovo V580                | 1         | 1.01%   |
| Lenovo Legion              | 1         | 1.01%   |
| Lenovo G570                | 1         | 1.01%   |
| Lenovo G50-70              | 1         | 1.01%   |
| Lenovo G50-45              | 1         | 1.01%   |
| IBM 2647NG8                | 1         | 1.01%   |
| HP ZBook                   | 1         | 1.01%   |
| HP OMEN                    | 1         | 1.01%   |
| HP Notebook                | 1         | 1.01%   |
| HP EliteBook               | 1         | 1.01%   |
| HP 255                     | 1         | 1.01%   |
| HP 2000                    | 1         | 1.01%   |
| Google Lulu                | 1         | 1.01%   |
| Google Chell               | 1         | 1.01%   |
| GEO GeoBook3               | 1         | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 13        | 13.13%  |
| 2020 | 11        | 11.11%  |
| 2017 | 8         | 8.08%   |
| 2015 | 7         | 7.07%   |
| 2014 | 7         | 7.07%   |
| 2012 | 7         | 7.07%   |
| 2021 | 6         | 6.06%   |
| 2011 | 6         | 6.06%   |
| 2008 | 6         | 6.06%   |
| 2018 | 5         | 5.05%   |
| 2016 | 5         | 5.05%   |
| 2013 | 5         | 5.05%   |
| 2010 | 5         | 5.05%   |
| 2009 | 3         | 3.03%   |
| 2022 | 2         | 2.02%   |
| 2006 | 2         | 2.02%   |
| 2004 | 1         | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 99        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 97.98%  |
| Yes  | 2         | 2.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 45        | 45%     |
| 4.01-8.0    | 23        | 23%     |
| 16.01-24.0  | 17        | 17%     |
| 32.01-64.0  | 4         | 4%      |
| 2.01-3.0    | 3         | 3%      |
| 0.51-1.0    | 3         | 3%      |
| 3.01-4.0    | 2         | 2%      |
| 64.01-256.0 | 2         | 2%      |
| 24.01-32.0  | 1         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 56        | 54.9%   |
| 0.51-1.0  | 29        | 28.43%  |
| 1.01-2.0  | 9         | 8.82%   |
| 2.01-3.0  | 4         | 3.92%   |
| 4.01-8.0  | 2         | 1.96%   |
| 3.01-4.0  | 1         | 0.98%   |
| 8.01-16.0 | 1         | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 74.75%  |
| 2      | 17        | 17.17%  |
| 0      | 6         | 6.06%   |
| 3      | 2         | 2.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 61%     |
| Yes       | 39        | 39%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 89%     |
| No        | 11        | 11%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 98.99%  |
| No        | 1         | 1.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 70.71%  |
| No        | 29        | 29.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 14        | 14.14%  |
| Germany     | 14        | 14.14%  |
| Russia      | 13        | 13.13%  |
| France      | 11        | 11.11%  |
| UK          | 8         | 8.08%   |
| Italy       | 5         | 5.05%   |
| Norway      | 3         | 3.03%   |
| Mexico      | 3         | 3.03%   |
| China       | 3         | 3.03%   |
| Turkey      | 2         | 2.02%   |
| Romania     | 2         | 2.02%   |
| Poland      | 2         | 2.02%   |
| Japan       | 2         | 2.02%   |
| Hungary     | 2         | 2.02%   |
| Colombia    | 2         | 2.02%   |
| Ukraine     | 1         | 1.01%   |
| Spain       | 1         | 1.01%   |
| South Korea | 1         | 1.01%   |
| Philippines | 1         | 1.01%   |
| Lithuania   | 1         | 1.01%   |
| Hong Kong   | 1         | 1.01%   |
| Finland     | 1         | 1.01%   |
| Denmark     | 1         | 1.01%   |
| Czechia     | 1         | 1.01%   |
| Bulgaria    | 1         | 1.01%   |
| Belarus     | 1         | 1.01%   |
| Australia   | 1         | 1.01%   |
| Argentina   | 1         | 1.01%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Moscow                | 9         | 8.91%   |
| Franconville          | 6         | 5.94%   |
| Whittier              | 3         | 2.97%   |
| Tijuana               | 3         | 2.97%   |
| Markt Indersdorf      | 3         | 2.97%   |
| Zwingenberg           | 2         | 1.98%   |
| Vollen                | 2         | 1.98%   |
| Setagaya-ku           | 2         | 1.98%   |
| Rome                  | 2         | 1.98%   |
| New Braunfels         | 2         | 1.98%   |
| Los Angeles           | 2         | 1.98%   |
| Istanbul              | 2         | 1.98%   |
| Hodmezovasarhely      | 2         | 1.98%   |
| Greenwich             | 2         | 1.98%   |
| Drobeta-Turnu Severin | 2         | 1.98%   |
| Changzhou             | 2         | 1.98%   |
| Woodland              | 1         | 0.99%   |
| Wloszczowa            | 1         | 0.99%   |
| Wissen                | 1         | 0.99%   |
| Wilhelmshaven         | 1         | 0.99%   |
| Warsaw                | 1         | 0.99%   |
| Vladimir              | 1         | 0.99%   |
| Vilnius               | 1         | 0.99%   |
| Vertou                | 1         | 0.99%   |
| Vaasa                 | 1         | 0.99%   |
| Ufa                   | 1         | 0.99%   |
| Trieste               | 1         | 0.99%   |
| Swindon               | 1         | 0.99%   |
| Suwon                 | 1         | 0.99%   |
| St Petersburg         | 1         | 0.99%   |
| Southampton           | 1         | 0.99%   |
| Sofia                 | 1         | 0.99%   |
| Shanghai              | 1         | 0.99%   |
| Sedavi                | 1         | 0.99%   |
| Sartrouville          | 1         | 0.99%   |
| San Bernardino        | 1         | 0.99%   |
| Saint-Denis           | 1         | 0.99%   |
| Rionegro              | 1         | 0.99%   |
| Portland              | 1         | 0.99%   |
| Pasig                 | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 27     | 19.44%  |
| WDC                 | 19        | 21     | 17.59%  |
| Toshiba             | 11        | 11     | 10.19%  |
| Seagate             | 11        | 12     | 10.19%  |
| SanDisk             | 6         | 6      | 5.56%   |
| Apple               | 5         | 6      | 4.63%   |
| Hitachi             | 4         | 5      | 3.7%    |
| Crucial             | 4         | 4      | 3.7%    |
| Micron Technology   | 3         | 3      | 2.78%   |
| Kingston            | 3         | 3      | 2.78%   |
| Intel               | 3         | 3      | 2.78%   |
| OCZ                 | 2         | 2      | 1.85%   |
| Gigabyte Technology | 2         | 2      | 1.85%   |
| Fujitsu             | 2         | 3      | 1.85%   |
| UMIS                | 1         | 1      | 0.93%   |
| Transcend           | 1         | 1      | 0.93%   |
| SPCC                | 1         | 1      | 0.93%   |
| SK hynix            | 1         | 2      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Phison              | 1         | 1      | 0.93%   |
| LITEONIT            | 1         | 1      | 0.93%   |
| KingDian            | 1         | 1      | 0.93%   |
| Intenso             | 1         | 1      | 0.93%   |
| HGST                | 1         | 1      | 0.93%   |
| Corsair             | 1         | 1      | 0.93%   |
| ASUSTek Computer    | 1         | 2      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 3         | 2.68%   |
| SanDisk pSSD 32GB                         | 3         | 2.68%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.79%   |
| Seagate ST95005620AS 500GB                | 2         | 1.79%   |
| SanDisk SSD U100 24GB                     | 2         | 1.79%   |
| Kingston SA400S37240G 240GB               | 2         | 1.79%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 1.79%   |
| Apple SSD SM0512F 500GB                   | 2         | 1.79%   |
| WDC WDS240G2G0A-00JH30 240GB              | 1         | 0.89%   |
| WDC WDS120G2G0B-00EPW0 120GB              | 1         | 0.89%   |
| WDC WDS120G1G0A-00SS50 120GB              | 1         | 0.89%   |
| WDC WD7500BPKX-00HPJT0 752GB              | 1         | 0.89%   |
| WDC WD7500BPKT-75PK4T0 752GB              | 1         | 0.89%   |
| WDC WD3200BEVT-75ZCT2 320GB               | 1         | 0.89%   |
| WDC WD3200BEKT-60PVMT0 320GB              | 1         | 0.89%   |
| WDC WD2500LPCX-24C6HT0 250GB              | 1         | 0.89%   |
| WDC WD2500BEVT-80A23T0 250GB              | 1         | 0.89%   |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 0.89%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 0.89%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 0.89%   |
| WDC WD10SMRW-11Y43S0 1TB                  | 1         | 0.89%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 0.89%   |
| WDC WD10JPVX-60JC3T0 1TB                  | 1         | 0.89%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.89%   |
| WDC WD10JPVT-08A1YT2 1TB                  | 1         | 0.89%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB        | 1         | 0.89%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB      | 1         | 0.89%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB      | 1         | 0.89%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1         | 0.89%   |
| UMIS RPJTJ256MED1OWX 256GB                | 1         | 0.89%   |
| Transcend TS512GSSD370S 512GB             | 1         | 0.89%   |
| Toshiba TR200 240GB                       | 1         | 0.89%   |
| Toshiba THNSNC128GBSJ                     | 1         | 0.89%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 0.89%   |
| Toshiba MK7575GSX 752GB                   | 1         | 0.89%   |
| Toshiba MK1637GSX 160GB                   | 1         | 0.89%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB       | 1         | 0.89%   |
| SPCC Solid State Disk 240GB               | 1         | 0.89%   |
| SK hynix SKHynix_HFS512GD9TNG-L5B0B 512GB | 1         | 0.89%   |
| Seagate ST9750423AS 752GB                 | 1         | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 14     | 34.15%  |
| Seagate | 11        | 12     | 26.83%  |
| Toshiba | 8         | 8      | 19.51%  |
| Hitachi | 4         | 5      | 9.76%   |
| Fujitsu | 2         | 3      | 4.88%   |
| HGST    | 1         | 1      | 2.44%   |
| Apple   | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 22.45%  |
| SanDisk             | 6         | 6      | 12.24%  |
| Apple               | 4         | 5      | 8.16%   |
| Toshiba             | 3         | 3      | 6.12%   |
| Kingston            | 3         | 3      | 6.12%   |
| Intel               | 3         | 3      | 6.12%   |
| Crucial             | 3         | 3      | 6.12%   |
| WDC                 | 2         | 3      | 4.08%   |
| OCZ                 | 2         | 2      | 4.08%   |
| Micron Technology   | 2         | 2      | 4.08%   |
| Gigabyte Technology | 2         | 2      | 4.08%   |
| Transcend           | 1         | 1      | 2.04%   |
| SPCC                | 1         | 1      | 2.04%   |
| PNY                 | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| KingDian            | 1         | 1      | 2.04%   |
| Intenso             | 1         | 1      | 2.04%   |
| Corsair             | 1         | 1      | 2.04%   |
| ASUSTek Computer    | 1         | 2      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 46        | 54     | 43.4%   |
| HDD  | 41        | 44     | 38.68%  |
| NVMe | 19        | 24     | 17.92%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 80        | 98     | 80.81%  |
| NVMe | 19        | 24     | 19.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 75     | 73.81%  |
| 0.51-1.0   | 21        | 22     | 25%     |
| 1.01-2.0   | 1         | 1      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 83        | 83.84%  |
| 101-250    | 6         | 6.06%   |
| 251-500    | 3         | 3.03%   |
| 51-100     | 3         | 3.03%   |
| 21-50      | 2         | 2.02%   |
| 501-1000   | 2         | 2.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 97        | 97%     |
| 21-50   | 2         | 2%      |
| 51-100  | 1         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 5%      |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 5%      |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 5%      |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 5%      |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 5%      |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 5%      |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 5%      |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 5%      |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 5%      |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 5%      |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 5%      |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 5%      |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 5%      |
| Hitachi HTS545050B9A300 500GB                    | 1         | 2      | 5%      |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 5%      |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 5%      |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 25%     |
| Toshiba             | 3         | 3      | 15%     |
| Seagate             | 3         | 3      | 15%     |
| Hitachi             | 3         | 4      | 15%     |
| SanDisk             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Corsair             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 33.33%  |
| Toshiba | 3         | 3      | 20%     |
| Seagate | 3         | 3      | 20%     |
| Hitachi | 3         | 4      | 20%     |
| HGST    | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 16     | 75%     |
| SSD  | 5         | 5      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model             | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| SanDisk pSSD 32GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 77        | 98     | 77.78%  |
| Malfunc  | 20        | 21     | 20.2%   |
| Detected | 1         | 2      | 1.01%   |
| Failed   | 1         | 1      | 1.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 74        | 66.07%  |
| Samsung Electronics                     | 14        | 12.5%   |
| AMD                                     | 12        | 10.71%  |
| SanDisk                                 | 4         | 3.57%   |
| VIA Technologies                        | 1         | 0.89%   |
| SK hynix                                | 1         | 0.89%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.89%   |
| Shenzhen Unionmemory Information System | 1         | 0.89%   |
| Phison Electronics                      | 1         | 0.89%   |
| Micron/Crucial Technology               | 1         | 0.89%   |
| Micron Technology                       | 1         | 0.89%   |
| JMicron Technology                      | 1         | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 9.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 6.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 5.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 5.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 4.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 4.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.48%   |
| Samsung SM951 AHCI                                                               | 2         | 1.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.65%   |
| Samsung Apple PCIe SSD                                                           | 2         | 1.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.65%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.65%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1.65%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.65%   |
| Unknown                                                                          | 2         | 1.65%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.83%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.83%   |
| SK hynix hynix unknown                                                           | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.83%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.83%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.83%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.83%   |
| Micron/Crucial NVMe Controller                                                   | 1         | 0.83%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.83%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                             | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 73        | 64.6%   |
| NVMe | 19        | 16.81%  |
| IDE  | 14        | 12.39%  |
| RAID | 7         | 6.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 87%     |
| AMD    | 13        | 13%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 4%      |
| Intel CPU Version                           | 3         | 3%      |
| Intel Core i7-4600U CPU @ 2.10GHz           | 3         | 3%      |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 3         | 3%      |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2%      |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2%      |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 2%      |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 2%      |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 2%      |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 2%      |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2%      |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 1%      |
| Intel Pentium III                           | 1         | 1%      |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1%      |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1%      |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 1%      |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 1%      |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 1%      |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1%      |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1%      |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1%      |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1%      |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1%      |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 1%      |
| Intel Core i7-4770HQ CPU @ 2.20GHz          | 1         | 1%      |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 1%      |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 1%      |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1%      |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1%      |
| Intel Core i7-4500U CPU                     | 1         | 1%      |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1%      |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1%      |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1%      |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1%      |
| Intel Core i7 CPU L 640 @ 2.13GHz           | 1         | 1%      |
| Intel Core i5-9300HF CPU @ 2.40GHz          | 1         | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1%      |
| Intel Core i5-7Y54 CPU @ 1.20GHz            | 1         | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 31        | 31%     |
| Intel Core i7     | 25        | 25%     |
| Intel Core i3     | 7         | 7%      |
| Other             | 6         | 6%      |
| Intel Core 2 Duo  | 4         | 4%      |
| Intel Pentium     | 3         | 3%      |
| Intel Atom        | 3         | 3%      |
| AMD Ryzen 7       | 3         | 3%      |
| AMD A6            | 3         | 3%      |
| Intel Celeron     | 2         | 2%      |
| AMD Ryzen 5       | 2         | 2%      |
| AMD A8            | 2         | 2%      |
| Intel Xeon        | 1         | 1%      |
| Intel Pentium III | 1         | 1%      |
| Intel Genuine     | 1         | 1%      |
| Intel Core m5     | 1         | 1%      |
| Intel Core i9     | 1         | 1%      |
| Intel Core 2      | 1         | 1%      |
| Intel Celeron M   | 1         | 1%      |
| AMD E1            | 1         | 1%      |
| AMD A10           | 1         | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 52        | 52%     |
| 4       | 30        | 30%     |
| Unknown | 8         | 8%      |
| 8       | 3         | 3%      |
| 1       | 3         | 3%      |
| 6       | 2         | 2%      |
| 16      | 1         | 1%      |
| 12      | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 67        | 67%     |
| 1       | 23        | 23%     |
| Unknown | 10        | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 19%     |
| Haswell       | 16        | 16%     |
| Skylake       | 11        | 11%     |
| IvyBridge     | 9         | 9%      |
| SandyBridge   | 7         | 7%      |
| Penryn        | 6         | 6%      |
| Puma          | 4         | 4%      |
| Bonnell       | 4         | 4%      |
| Zen+          | 3         | 3%      |
| Core          | 3         | 3%      |
| Broadwell     | 3         | 3%      |
| Westmere      | 2         | 2%      |
| Silvermont    | 2         | 2%      |
| P6            | 2         | 2%      |
| Unknown       | 2         | 2%      |
| TigerLake     | 1         | 1%      |
| Steamroller   | 1         | 1%      |
| K10 Llano     | 1         | 1%      |
| Jaguar        | 1         | 1%      |
| Goldmont plus | 1         | 1%      |
| Excavator     | 1         | 1%      |
| CometLake     | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 73        | 65.18%  |
| AMD              | 20        | 17.86%  |
| Nvidia           | 17        | 15.18%  |
| VIA Technologies | 1         | 0.89%   |
| S3 Graphics      | 1         | 0.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 8.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 6.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 6.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 3.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.59%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.59%   |
| Intel HD Graphics 620                                                                    | 3         | 2.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.59%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 2.59%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.72%   |
| AMD Lucienne                                                                             | 2         | 1.72%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.86%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.86%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.86%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.86%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.86%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.86%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.86%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.86%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.86%   |
| Nvidia GK107M [GeForce GT 645M]                                                          | 1         | 0.86%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.86%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.86%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 0.86%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.86%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 0.86%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.86%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 55        | 55%     |
| 1 x AMD         | 17        | 17%     |
| Intel + Nvidia  | 9         | 9%      |
| 2 x Intel       | 7         | 7%      |
| 1 x Nvidia      | 7         | 7%      |
| Intel + AMD     | 2         | 2%      |
| 1 x VIA         | 1         | 1%      |
| 1 x S3 Graphics | 1         | 1%      |
| AMD + Nvidia    | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 81        | 81.82%  |
| Unknown     | 14        | 14.14%  |
| Proprietary | 4         | 4.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 87%     |
| 0.01-0.5   | 6         | 6%      |
| 0.51-1.0   | 4         | 4%      |
| 1.01-2.0   | 3         | 3%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 17.28%  |
| AU Optronics            | 14        | 17.28%  |
| BOE                     | 11        | 13.58%  |
| Samsung Electronics     | 10        | 12.35%  |
| Chimei Innolux          | 7         | 8.64%   |
| Chi Mei Optoelectronics | 4         | 4.94%   |
| Apple                   | 4         | 4.94%   |
| Sharp                   | 3         | 3.7%    |
| Lenovo                  | 3         | 3.7%    |
| Panasonic               | 2         | 2.47%   |
| HannStar                | 2         | 2.47%   |
| LG Philips              | 1         | 1.23%   |
| Hewlett-Packard         | 1         | 1.23%   |
| Goldstar                | 1         | 1.23%   |
| CPT                     | 1         | 1.23%   |
| BenQ                    | 1         | 1.23%   |
| AOC                     | 1         | 1.23%   |
| Acer                    | 1         | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 2         | 2.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 2         | 2.44%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 2         | 2.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 2         | 2.44%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 2         | 2.44%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 2.44%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 2         | 2.44%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 2.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 2.44%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                  | 1         | 1.22%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.22%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                  | 1         | 1.22%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch    | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 1.22%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD0612 1920x1080 340x190mm 15.3-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.22%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch              | 1         | 1.22%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch              | 1         | 1.22%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 1         | 1.22%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 1         | 1.22%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.22%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch               | 1         | 1.22%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 32        | 39.51%  |
| 1920x1080 (FHD)  | 24        | 29.63%  |
| 1600x900 (HD+)   | 5         | 6.17%   |
| 1280x800 (WXGA)  | 4         | 4.94%   |
| 1024x600         | 4         | 4.94%   |
| 1440x900 (WXGA+) | 3         | 3.7%    |
| 3840x2160 (4K)   | 2         | 2.47%   |
| 2880x1800        | 2         | 2.47%   |
| 2880x1620        | 2         | 2.47%   |
| 3200x1800 (QHD+) | 1         | 1.23%   |
| 2560x1440 (QHD)  | 1         | 1.23%   |
| 1280x1024 (SXGA) | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 35        | 42.68%  |
| 13     | 19        | 23.17%  |
| 17     | 7         | 8.54%   |
| 12     | 7         | 8.54%   |
| 10     | 4         | 4.88%   |
| 24     | 3         | 3.66%   |
| 11     | 3         | 3.66%   |
| 27     | 2         | 2.44%   |
| 18     | 1         | 1.22%   |
| 14     | 1         | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 57.32%  |
| 201-300     | 23        | 28.05%  |
| 351-400     | 6         | 7.32%   |
| 501-600     | 4         | 4.88%   |
| 601-700     | 1         | 1.22%   |
| 401-500     | 1         | 1.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 66        | 86.84%  |
| 16/10 | 8         | 10.53%  |
| 5/4   | 1         | 1.32%   |
| 3/2   | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 27        | 32.93%  |
| 81-90          | 15        | 18.29%  |
| 101-110        | 8         | 9.76%   |
| 61-70          | 7         | 8.54%   |
| 71-80          | 5         | 6.1%    |
| 121-130        | 5         | 6.1%    |
| 41-50          | 4         | 4.88%   |
| 51-60          | 3         | 3.66%   |
| 201-250        | 3         | 3.66%   |
| 301-350        | 2         | 2.44%   |
| 141-150        | 2         | 2.44%   |
| 131-140        | 1         | 1.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 34        | 41.98%  |
| 121-160       | 24        | 29.63%  |
| 161-240       | 10        | 12.35%  |
| 51-100        | 10        | 12.35%  |
| More than 240 | 3         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 78        | 77.23%  |
| 0     | 19        | 18.81%  |
| 2     | 3         | 2.97%   |
| 3     | 1         | 0.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 58        | 37.91%  |
| Realtek Semiconductor             | 41        | 26.8%   |
| Qualcomm Atheros                  | 24        | 15.69%  |
| Broadcom                          | 11        | 7.19%   |
| Ralink                            | 3         | 1.96%   |
| TP-Link                           | 2         | 1.31%   |
| Marvell Technology Group          | 2         | 1.31%   |
| Ericsson Business Mobile Networks | 2         | 1.31%   |
| VIA Technologies                  | 1         | 0.65%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.65%   |
| Sierra Wireless                   | 1         | 0.65%   |
| Samsung Electronics               | 1         | 0.65%   |
| Ralink Technology                 | 1         | 0.65%   |
| Qualcomm                          | 1         | 0.65%   |
| JMicron Technology                | 1         | 0.65%   |
| Fibocom                           | 1         | 0.65%   |
| Atheros                           | 1         | 0.65%   |
| Apple                             | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 27        | 13.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 12        | 5.91%   |
| Intel Wireless 7260                                                         | 9         | 4.43%   |
| Intel Wireless 8260                                                         | 7         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 5         | 2.46%   |
| Intel Wireless 3165                                                         | 5         | 2.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 4         | 1.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 4         | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 1.97%   |
| Intel Wireless 8265 / 8275                                                  | 4         | 1.97%   |
| Intel Ethernet Connection I217-LM                                           | 4         | 1.97%   |
| Intel Ethernet Connection (4) I219-LM                                       | 4         | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 4         | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 3         | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 3         | 1.48%   |
| Intel WiFi Link 5100                                                        | 3         | 1.48%   |
| Intel Ethernet Connection I219-LM                                           | 3         | 1.48%   |
| Intel Ethernet Connection I218-LM                                           | 3         | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 3         | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 3         | 1.48%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                           | 3         | 1.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 3         | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 2         | 0.99%   |
| Intel Wireless 7265                                                         | 2         | 0.99%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 0.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 2         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                                        | 2         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 0.99%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 0.99%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 0.99%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                             | 2         | 0.99%   |
| VIA VT6102/VT6103 [Rhine-II]                                                | 1         | 0.49%   |
| TP-Link TP-LINK Wireless USB Adapter                                        | 1         | 0.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter               | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 55        | 51.89%  |
| Qualcomm Atheros      | 19        | 17.92%  |
| Realtek Semiconductor | 16        | 15.09%  |
| Broadcom              | 8         | 7.55%   |
| Ralink                | 3         | 2.83%   |
| TP-Link               | 2         | 1.89%   |
| Sierra Wireless       | 1         | 0.94%   |
| Ralink Technology     | 1         | 0.94%   |
| Atheros               | 1         | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 9         | 8.26%   |
| Intel Wireless 8260                                            | 7         | 6.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 4.59%   |
| Intel Wireless 3165                                            | 5         | 4.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 3.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 3.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 3.67%   |
| Intel Wireless 8265 / 8275                                     | 4         | 3.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.75%   |
| Intel WiFi Link 5100                                           | 3         | 2.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 1.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.83%   |
| Intel Wireless 7265                                            | 2         | 1.83%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.83%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.83%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.83%   |
| TP-Link TP-LINK Wireless USB Adapter                           | 1         | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.92%   |
| Sierra Wireless EM7455                                         | 1         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.92%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 0.92%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1         | 0.92%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 0.92%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.92%   |
| Intel Wireless-AC 9260                                         | 1         | 0.92%   |
| Intel WiMAX/WiFi Link 5150                                     | 1         | 0.92%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 39        | 43.33%  |
| Intel                            | 30        | 33.33%  |
| Qualcomm Atheros                 | 7         | 7.78%   |
| Broadcom                         | 6         | 6.67%   |
| Marvell Technology Group         | 2         | 2.22%   |
| VIA Technologies                 | 1         | 1.11%   |
| Silicon Integrated Systems [SiS] | 1         | 1.11%   |
| Samsung Electronics              | 1         | 1.11%   |
| Qualcomm                         | 1         | 1.11%   |
| JMicron Technology               | 1         | 1.11%   |
| Apple                            | 1         | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 29.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 13.19%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 4.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 4.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.4%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 3.3%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 3.3%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 3.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.2%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.2%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.2%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 2.2%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.1%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.1%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.1%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 1.1%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.1%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.1%    |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.1%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.1%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.1%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.1%    |
| Intel Ethernet Connection I219-V                                  | 1         | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.1%    |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 1.1%    |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.1%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.1%    |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.1%    |
| Apple Ethernet Adapter [A1277]                                    | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 51.85%  |
| Ethernet | 88        | 46.56%  |
| Unknown  | 3         | 1.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 79        | 51.97%  |
| WiFi     | 71        | 46.71%  |
| Unknown  | 2         | 1.32%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 87        | 87%     |
| 1     | 13        | 13%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 89        | 89%     |
| Yes  | 11        | 11%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 44.44%  |
| Realtek Semiconductor           | 7         | 9.72%   |
| Broadcom                        | 6         | 8.33%   |
| Qualcomm Atheros Communications | 5         | 6.94%   |
| Lite-On Technology              | 5         | 6.94%   |
| ASUSTek Computer                | 4         | 5.56%   |
| Apple                           | 4         | 5.56%   |
| IMC Networks                    | 3         | 4.17%   |
| Foxconn / Hon Hai               | 2         | 2.78%   |
| Hewlett-Packard                 | 1         | 1.39%   |
| Dell                            | 1         | 1.39%   |
| Cambridge Silicon Radio         | 1         | 1.39%   |
| Alps Electric                   | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 21        | 29.17%  |
| Intel AX201 Bluetooth                                       | 4         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 4.17%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.78%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.78%   |
| Intel AX200 Bluetooth                                       | 2         | 2.78%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 2.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.78%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.78%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 2.78%   |
| Apple Bluetooth Host Controller                             | 2         | 2.78%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 2.78%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.39%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.39%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.39%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.39%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.39%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.39%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.39%   |
| Lite-On Bluetooth USB Module                                | 1         | 1.39%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.39%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.39%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.39%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.39%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.39%   |
| Broadcom Broadcom Bluetooth 4.0                             | 1         | 1.39%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.39%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.39%   |
| ASUS ASUS USB-BT500                                         | 1         | 1.39%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 84        | 75.68%  |
| AMD                              | 17        | 15.32%  |
| Nvidia                           | 6         | 5.41%   |
| VIA Technologies                 | 1         | 0.9%    |
| Silicon Integrated Systems [SiS] | 1         | 0.9%    |
| Realtek Semiconductor            | 1         | 0.9%    |
| Blue Microphones                 | 1         | 0.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 11.97%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 7.04%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 7.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 6.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.63%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 4.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 3.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 3.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 3.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.11%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.41%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.7%    |
| Realtek Semiconductor Realtek USB Audio                                                           | 1         | 0.7%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.7%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.7%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.7%    |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.7%    |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.7%    |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.7%    |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.7%    |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.7%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 34.17%  |
| SK hynix            | 27        | 22.5%   |
| Micron Technology   | 12        | 10%     |
| Unknown             | 10        | 8.33%   |
| Kingston            | 7         | 5.83%   |
| Elpida              | 4         | 3.33%   |
| Crucial             | 4         | 3.33%   |
| Transcend           | 2         | 1.67%   |
| Ramaxel Technology  | 2         | 1.67%   |
| A-DATA Technology   | 2         | 1.67%   |
| Unknown             | 2         | 1.67%   |
| Unknown (ABCD)      | 1         | 0.83%   |
| Unknown (09D5)      | 1         | 0.83%   |
| Nanya Technology    | 1         | 0.83%   |
| Magnum Tech         | 1         | 0.83%   |
| G.Skill             | 1         | 0.83%   |
| Corsair             | 1         | 0.83%   |
| 48spaces            | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 7         | 5.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 3.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.31%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 2.31%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 2.31%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.31%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.54%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.54%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 2         | 1.54%   |
| Unknown                                                          | 2         | 1.54%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                        | 1         | 0.77%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                        | 1         | 0.77%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 0.77%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.77%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.77%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.77%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                       | 1         | 0.77%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.77%   |
| Unknown RAM Module 128MB SODIMM SDRAM                            | 1         | 0.77%   |
| Unknown RAM Module 1024MB SODIMM RAM                             | 1         | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 1         | 0.77%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s              | 1         | 0.77%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                   | 1         | 0.77%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                 | 1         | 0.77%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.77%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 1         | 0.77%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.77%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.77%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.77%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.77%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 48        | 47.52%  |
| DDR4    | 31        | 30.69%  |
| DDR2    | 8         | 7.92%   |
| LPDDR3  | 5         | 4.95%   |
| SDRAM   | 3         | 2.97%   |
| Unknown | 2         | 1.98%   |
| RAM     | 1         | 0.99%   |
| LPDDR4  | 1         | 0.99%   |
| DRAM    | 1         | 0.99%   |
| DDR     | 1         | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 94.06%  |
| Chip         | 3         | 2.97%   |
| Unknown      | 2         | 1.98%   |
| Row Of Chips | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 49        | 42.24%  |
| 8192  | 34        | 29.31%  |
| 2048  | 17        | 14.66%  |
| 16384 | 8         | 6.9%    |
| 1024  | 4         | 3.45%   |
| 32768 | 2         | 1.72%   |
| 512   | 1         | 0.86%   |
| 128   | 1         | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 35        | 31.82%  |
| 2400    | 13        | 11.82%  |
| 2667    | 12        | 10.91%  |
| 2133    | 8         | 7.27%   |
| 1334    | 8         | 7.27%   |
| 3200    | 6         | 5.45%   |
| 667     | 6         | 5.45%   |
| 1867    | 5         | 4.55%   |
| 1333    | 5         | 4.55%   |
| Unknown | 5         | 4.55%   |
| 1067    | 2         | 1.82%   |
| 800     | 2         | 1.82%   |
| 1866    | 1         | 0.91%   |
| 975     | 1         | 0.91%   |
| 533     | 1         | 0.91%   |

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
| Chicony Electronics                    | 21        | 26.92%  |
| Bison Electronics                      | 9         | 11.54%  |
| Realtek Semiconductor                  | 8         | 10.26%  |
| Suyin                                  | 7         | 8.97%   |
| Sunplus Innovation Technology          | 7         | 8.97%   |
| Microdia                               | 5         | 6.41%   |
| IMC Networks                           | 5         | 6.41%   |
| Silicon Motion                         | 3         | 3.85%   |
| Lite-On Technology                     | 3         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.85%   |
| Quanta                                 | 2         | 2.56%   |
| Logitech                               | 1         | 1.28%   |
| Intel                                  | 1         | 1.28%   |
| Genesys Logic                          | 1         | 1.28%   |
| Apple                                  | 1         | 1.28%   |
| Alcor Micro                            | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 8.97%   |
| Bison Integrated Camera                             | 5         | 6.41%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 5.13%   |
| Suyin Acer Crystal Eye webcam                       | 2         | 2.56%   |
| Realtek Realtek USB2.0 PC Camera                    | 2         | 2.56%   |
| Realtek Lenovo EasyCamera                           | 2         | 2.56%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.56%   |
| Microdia Integrated Webcam                          | 2         | 2.56%   |
| IMC Networks EasyCamera                             | 2         | 2.56%   |
| Chicony HD WebCam                                   | 2         | 2.56%   |
| Chicony Chicony USB2.0 Camera                       | 2         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 2.56%   |
| Suyin USB 2.0 UVC 1.3M WebCam                       | 1         | 1.28%   |
| Suyin Laptop_Integrated_Webcam_3M                   | 1         | 1.28%   |
| Suyin HD WebCam                                     | 1         | 1.28%   |
| Suyin HD Video WebCam                               | 1         | 1.28%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.28%   |
| Sunplus Integrated Webcam                           | 1         | 1.28%   |
| Sunplus Asus Webcam                                 | 1         | 1.28%   |
| Silicon Motion WebCam SCX Series                    | 1         | 1.28%   |
| Silicon Motion Realtek USB2.0 PC Camera             | 1         | 1.28%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 1.28%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 1.28%   |
| Realtek USB Camera                                  | 1         | 1.28%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.28%   |
| Realtek HD Webcam - Realtek                         | 1         | 1.28%   |
| Quanta Realtek DMFT - RGB                           | 1         | 1.28%   |
| Quanta Front camera                                 | 1         | 1.28%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.28%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.28%   |
| Lite-On Realtek PC Camera                           | 1         | 1.28%   |
| Lite-On Integrated Camera                           | 1         | 1.28%   |
| Lite-On HP Universal Camera                         | 1         | 1.28%   |
| Intel WiMAX Connection 2400m                        | 1         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.28%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.28%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.28%   |
| Genesys Logic Camera                                | 1         | 1.28%   |
| Chicony Webcam                                      | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 10        | 50%     |
| Synaptics             | 4         | 20%     |
| Upek                  | 3         | 15%     |
| LighTuning Technology | 1         | 5%      |
| Broadcom              | 1         | 5%      |
| AuthenTec             | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 15%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 15%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 15%     |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 5%      |
| Validity Sensors Synaptics WBDI                                              | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5%      |
| LighTuning Fingerprint Reader                                                | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |
| AuthenTec AES1600                                                            | 1         | 5%      |
| Unknown                                                                      | 1         | 5%      |

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
| 1     | 32        | 31.37%  |
| 2     | 29        | 28.43%  |
| 3     | 15        | 14.71%  |
| 0     | 14        | 13.73%  |
| 4     | 9         | 8.82%   |
| 7     | 1         | 0.98%   |
| 6     | 1         | 0.98%   |
| 5     | 1         | 0.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 67        | 39.64%  |
| Net/wireless             | 31        | 18.34%  |
| Fingerprint reader       | 20        | 11.83%  |
| Bluetooth                | 20        | 11.83%  |
| Card reader              | 19        | 11.24%  |
| Firewire controller      | 9         | 5.33%   |
| Storage/raid             | 1         | 0.59%   |
| Sound                    | 1         | 0.59%   |
| Network                  | 1         | 0.59%   |

