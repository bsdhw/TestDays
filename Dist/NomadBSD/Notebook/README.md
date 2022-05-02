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

Total: 117

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| NomadBSD 1.3.2    | 34        | 36.96%  |
| NomadBSD 5806f915 | 27        | 29.35%  |
| NomadBSD 1.4      | 18        | 19.57%  |
| NomadBSD 1.3.1    | 7         | 7.61%   |
| NomadBSD 1.4-RC1  | 6         | 6.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| NomadBSD | 88        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 82        | 92.13%  |
| i386  | 7         | 7.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 80        | 90.91%  |
| GNOME   | 6         | 6.82%   |
| XFCE    | 1         | 1.14%   |
| KDE5    | 1         | 1.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 88        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 88        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 34        | 38.2%   |
| Unknown | 15        | 16.85%  |
| de_DE   | 10        | 11.24%  |
| en_GB   | 6         | 6.74%   |
| ru_RU   | 5         | 5.62%   |
| zh_CN   | 3         | 3.37%   |
| it_IT   | 3         | 3.37%   |
| pl_PL   | 2         | 2.25%   |
| hu_HU   | 2         | 2.25%   |
| fr_FR   | 2         | 2.25%   |
| es_ES   | 2         | 2.25%   |
| tr_TR   | 1         | 1.12%   |
| ko_KR   | 1         | 1.12%   |
| en_AU   | 1         | 1.12%   |
| cs_CZ   | 1         | 1.12%   |
| bg_BG   | 1         | 1.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 83        | 93.26%  |
| BIOS | 6         | 6.74%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 81        | 92.05%  |
| Zfs  | 7         | 7.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 59        | 66.29%  |
| MBR  | 30        | 33.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 19        | 21.59%  |
| Dell                | 14        | 15.91%  |
| Hewlett-Packard     | 12        | 13.64%  |
| ASUSTek Computer    | 10        | 11.36%  |
| Acer                | 6         | 6.82%   |
| Apple               | 4         | 4.55%   |
| Sony                | 3         | 3.41%   |
| Samsung Electronics | 2         | 2.27%   |
| Notebook            | 2         | 2.27%   |
| Google              | 2         | 2.27%   |
| Fujitsu             | 2         | 2.27%   |
| TUXEDO              | 1         | 1.14%   |
| Toshiba             | 1         | 1.14%   |
| Pegatron            | 1         | 1.14%   |
| Panasonic           | 1         | 1.14%   |
| NEC Computers       | 1         | 1.14%   |
| MSI                 | 1         | 1.14%   |
| IBM                 | 1         | 1.14%   |
| GEO                 | 1         | 1.14%   |
| Fujitsu Siemens     | 1         | 1.14%   |
| Clevo               | 1         | 1.14%   |
| Alienware           | 1         | 1.14%   |
| Unknown             | 1         | 1.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 2.27%   |
| Toshiba Satellite C660                   | 1         | 1.14%   |
| Sony VPCM13M1R                           | 1         | 1.14%   |
| Sony VJS121C11N                          | 1         | 1.14%   |
| Sony SVE1713S1RW                         | 1         | 1.14%   |
| Samsung N145P/N250P/N260P                | 1         | 1.14%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 1.14%   |
| Pegatron T12Ah                           | 1         | 1.14%   |
| Panasonic CF-C1BD06EFG                   | 1         | 1.14%   |
| Notebook W650DC,DD                       | 1         | 1.14%   |
| Notebook N650DU                          | 1         | 1.14%   |
| NEC Computers PC-GL186Y3AZ               | 1         | 1.14%   |
| MSI MS-N033                              | 1         | 1.14%   |
| Lenovo ThinkPad X201 Tablet 311396U      | 1         | 1.14%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU | 1         | 1.14%   |
| Lenovo ThinkPad W541 20EGS04800          | 1         | 1.14%   |
| Lenovo ThinkPad T530 24295VU             | 1         | 1.14%   |
| Lenovo ThinkPad T510 4384FF3             | 1         | 1.14%   |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 1.14%   |
| Lenovo ThinkPad T490 20RYS06R00          | 1         | 1.14%   |
| Lenovo ThinkPad T470s W10DG 20JS001FGE   | 1         | 1.14%   |
| Lenovo ThinkPad T460 20FMS78014          | 1         | 1.14%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 1.14%   |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 1.14%   |
| Lenovo ThinkPad T440p 20AWS0VK00         | 1         | 1.14%   |
| Lenovo ThinkPad T430 2347C32             | 1         | 1.14%   |
| Lenovo ThinkPad S1 Yoga 20C0S0M300       | 1         | 1.14%   |
| Lenovo Legion Y7000 2019 PG0 81T0        | 1         | 1.14%   |
| Lenovo IdeaPad S145-15API 81UT           | 1         | 1.14%   |
| Lenovo IdeaPad 110-15IBR 80T7            | 1         | 1.14%   |
| Lenovo G570 20079                        | 1         | 1.14%   |
| Lenovo G50-45 80E3                       | 1         | 1.14%   |
| IBM 2647NG8                              | 1         | 1.14%   |
| HP ZBook Studio G3                       | 1         | 1.14%   |
| HP ProBook 640 G1                        | 1         | 1.14%   |
| HP ProBook 450 G2                        | 1         | 1.14%   |
| HP Pavilion Notebook                     | 1         | 1.14%   |
| HP Pavilion g6                           | 1         | 1.14%   |
| HP Pavilion dv6000 (RP981EA#AB8)         | 1         | 1.14%   |
| HP OMEN by HP Laptop 17-cb1xxx           | 1         | 1.14%   |
| HP Notebook                              | 1         | 1.14%   |
| HP Laptop 15-db0xxx                      | 1         | 1.14%   |
| HP Laptop 15-da0xxx                      | 1         | 1.14%   |
| HP EliteBook 820 G1                      | 1         | 1.14%   |
| HP 2000                                  | 1         | 1.14%   |
| Google Lulu                              | 1         | 1.14%   |
| Google Chell                             | 1         | 1.14%   |
| GEO GeoBook3                             | 1         | 1.14%   |
| Fujitsu Siemens AMILO PRO V3515          | 1         | 1.14%   |
| Fujitsu LIFEBOOK E754                    | 1         | 1.14%   |
| Fujitsu LIFEBOOK E736                    | 1         | 1.14%   |
| Dell Vostro 3750                         | 1         | 1.14%   |
| Dell Studio 1555                         | 1         | 1.14%   |
| Dell Precision 7530                      | 1         | 1.14%   |
| Dell Latitude E7240                      | 1         | 1.14%   |
| Dell Latitude D630                       | 1         | 1.14%   |
| Dell Latitude 5490                       | 1         | 1.14%   |
| Dell Latitude 5480                       | 1         | 1.14%   |
| Dell Latitude 5400                       | 1         | 1.14%   |
| Dell Latitude 5290                       | 1         | 1.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 14        | 15.91%  |
| Dell Latitude              | 8         | 9.09%   |
| Acer Aspire                | 6         | 6.82%   |
| HP Pavilion                | 3         | 3.41%   |
| Dell Inspiron              | 3         | 3.41%   |
| Lenovo IdeaPad             | 2         | 2.27%   |
| HP ProBook                 | 2         | 2.27%   |
| HP Laptop                  | 2         | 2.27%   |
| Fujitsu LIFEBOOK           | 2         | 2.27%   |
| Unknown                    | 2         | 2.27%   |
| Toshiba Satellite          | 1         | 1.14%   |
| Sony VPCM13M1R             | 1         | 1.14%   |
| Sony VJS121C11N            | 1         | 1.14%   |
| Sony SVE1713S1RW           | 1         | 1.14%   |
| Samsung N145P              | 1         | 1.14%   |
| Samsung 300E5EV            | 1         | 1.14%   |
| Pegatron T12Ah             | 1         | 1.14%   |
| Panasonic CF-C1BD06EFG     | 1         | 1.14%   |
| Notebook W650DC            | 1         | 1.14%   |
| Notebook N650DU            | 1         | 1.14%   |
| NEC Computers PC-GL186Y3AZ | 1         | 1.14%   |
| MSI MS-N033                | 1         | 1.14%   |
| Lenovo Legion              | 1         | 1.14%   |
| Lenovo G570                | 1         | 1.14%   |
| Lenovo G50-45              | 1         | 1.14%   |
| IBM 2647NG8                | 1         | 1.14%   |
| HP ZBook                   | 1         | 1.14%   |
| HP OMEN                    | 1         | 1.14%   |
| HP Notebook                | 1         | 1.14%   |
| HP EliteBook               | 1         | 1.14%   |
| HP 2000                    | 1         | 1.14%   |
| Google Lulu                | 1         | 1.14%   |
| Google Chell               | 1         | 1.14%   |
| GEO GeoBook3               | 1         | 1.14%   |
| Fujitsu Siemens AMILO      | 1         | 1.14%   |
| Dell Vostro                | 1         | 1.14%   |
| Dell Studio                | 1         | 1.14%   |
| Dell Precision             | 1         | 1.14%   |
| Clevo W55xEU               | 1         | 1.14%   |
| ASUS X751LN                | 1         | 1.14%   |
| ASUS X71SL                 | 1         | 1.14%   |
| ASUS X550LC                | 1         | 1.14%   |
| ASUS X540YA                | 1         | 1.14%   |
| ASUS X202E                 | 1         | 1.14%   |
| ASUS VivoBook              | 1         | 1.14%   |
| ASUS TUF                   | 1         | 1.14%   |
| ASUS N75SF                 | 1         | 1.14%   |
| ASUS M51Sr                 | 1         | 1.14%   |
| ASUS 1000                  | 1         | 1.14%   |
| Apple MacBookPro8          | 1         | 1.14%   |
| Apple MacBookPro11         | 1         | 1.14%   |
| Apple MacBookAir7          | 1         | 1.14%   |
| Apple MacBookAir6          | 1         | 1.14%   |
| Alienware M18xR1           | 1         | 1.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 13        | 14.77%  |
| 2020 | 10        | 11.36%  |
| 2017 | 8         | 9.09%   |
| 2015 | 7         | 7.95%   |
| 2014 | 6         | 6.82%   |
| 2011 | 6         | 6.82%   |
| 2008 | 6         | 6.82%   |
| 2016 | 5         | 5.68%   |
| 2012 | 5         | 5.68%   |
| 2010 | 5         | 5.68%   |
| 2018 | 4         | 4.55%   |
| 2013 | 4         | 4.55%   |
| 2021 | 3         | 3.41%   |
| 2009 | 2         | 2.27%   |
| 2006 | 2         | 2.27%   |
| 2022 | 1         | 1.14%   |
| 2004 | 1         | 1.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 88        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 86        | 97.73%  |
| Yes  | 2         | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 39        | 43.82%  |
| 4.01-8.0    | 22        | 24.72%  |
| 16.01-24.0  | 14        | 15.73%  |
| 32.01-64.0  | 4         | 4.49%   |
| 2.01-3.0    | 3         | 3.37%   |
| 0.51-1.0    | 3         | 3.37%   |
| 3.01-4.0    | 2         | 2.25%   |
| 24.01-32.0  | 1         | 1.12%   |
| 64.01-256.0 | 1         | 1.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 50        | 54.95%  |
| 0.51-1.0  | 26        | 28.57%  |
| 1.01-2.0  | 8         | 8.79%   |
| 2.01-3.0  | 3         | 3.3%    |
| 4.01-8.0  | 2         | 2.2%    |
| 3.01-4.0  | 1         | 1.1%    |
| 8.01-16.0 | 1         | 1.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 68        | 77.27%  |
| 2      | 12        | 13.64%  |
| 0      | 6         | 6.82%   |
| 3      | 2         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 59.55%  |
| Yes       | 36        | 40.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 88.76%  |
| No        | 10        | 11.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 98.86%  |
| No        | 1         | 1.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 70.45%  |
| No        | 26        | 29.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 13        | 14.77%  |
| Russia      | 11        | 12.5%   |
| Germany     | 11        | 12.5%   |
| France      | 10        | 11.36%  |
| UK          | 7         | 7.95%   |
| Italy       | 5         | 5.68%   |
| Mexico      | 3         | 3.41%   |
| China       | 3         | 3.41%   |
| Turkey      | 2         | 2.27%   |
| Romania     | 2         | 2.27%   |
| Poland      | 2         | 2.27%   |
| Norway      | 2         | 2.27%   |
| Japan       | 2         | 2.27%   |
| Hungary     | 2         | 2.27%   |
| Colombia    | 2         | 2.27%   |
| Ukraine     | 1         | 1.14%   |
| Spain       | 1         | 1.14%   |
| South Korea | 1         | 1.14%   |
| Philippines | 1         | 1.14%   |
| Hong Kong   | 1         | 1.14%   |
| Denmark     | 1         | 1.14%   |
| Czechia     | 1         | 1.14%   |
| Bulgaria    | 1         | 1.14%   |
| Belarus     | 1         | 1.14%   |
| Australia   | 1         | 1.14%   |
| Argentina   | 1         | 1.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Moscow                | 8         | 8.89%   |
| Franconville          | 6         | 6.67%   |
| Whittier              | 3         | 3.33%   |
| Tijuana               | 3         | 3.33%   |
| Markt Indersdorf      | 3         | 3.33%   |
| Zwingenberg           | 2         | 2.22%   |
| Setagaya-ku           | 2         | 2.22%   |
| Rome                  | 2         | 2.22%   |
| New Braunfels         | 2         | 2.22%   |
| Los Angeles           | 2         | 2.22%   |
| Istanbul              | 2         | 2.22%   |
| Hodmezovasarhely      | 2         | 2.22%   |
| Greenwich             | 2         | 2.22%   |
| Drobeta-Turnu Severin | 2         | 2.22%   |
| Changzhou             | 2         | 2.22%   |
| Woodland              | 1         | 1.11%   |
| Wloszczowa            | 1         | 1.11%   |
| Wissen                | 1         | 1.11%   |
| Wilhelmshaven         | 1         | 1.11%   |
| Warsaw                | 1         | 1.11%   |
| Vollen                | 1         | 1.11%   |
| Vladimir              | 1         | 1.11%   |
| Vertou                | 1         | 1.11%   |
| Trieste               | 1         | 1.11%   |
| Swindon               | 1         | 1.11%   |
| Suwon                 | 1         | 1.11%   |
| St Petersburg         | 1         | 1.11%   |
| Southampton           | 1         | 1.11%   |
| Sofia                 | 1         | 1.11%   |
| Shanghai              | 1         | 1.11%   |
| Sedavi                | 1         | 1.11%   |
| San Bernardino        | 1         | 1.11%   |
| Saint-Denis           | 1         | 1.11%   |
| Rionegro              | 1         | 1.11%   |
| Pasig                 | 1         | 1.11%   |
| Paris                 | 1         | 1.11%   |
| Palmer                | 1         | 1.11%   |
| Oslo                  | 1         | 1.11%   |
| Nueve de Julio        | 1         | 1.11%   |
| Novosibirsk           | 1         | 1.11%   |
| Munich                | 1         | 1.11%   |
| Mogilev               | 1         | 1.11%   |
| Milan                 | 1         | 1.11%   |
| McDonough             | 1         | 1.11%   |
| Malton                | 1         | 1.11%   |
| London                | 1         | 1.11%   |
| Kyiv                  | 1         | 1.11%   |
| Kowloon               | 1         | 1.11%   |
| Hranice               | 1         | 1.11%   |
| Greifswald            | 1         | 1.11%   |
| Grafing bei Munchen   | 1         | 1.11%   |
| Glasgow               | 1         | 1.11%   |
| Fontenay-sous-Bois    | 1         | 1.11%   |
| DÃ¼sseldorf         | 1         | 1.11%   |
| Cupertino             | 1         | 1.11%   |
| Copenhagen            | 1         | 1.11%   |
| Chino Hills           | 1         | 1.11%   |
| Brisbane              | 1         | 1.11%   |
| Brighton              | 1         | 1.11%   |
| Bologna               | 1         | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 19     | 17.89%  |
| Samsung Electronics | 17        | 21     | 17.89%  |
| Toshiba             | 11        | 11     | 11.58%  |
| Seagate             | 11        | 12     | 11.58%  |
| SanDisk             | 5         | 5      | 5.26%   |
| Apple               | 5         | 6      | 5.26%   |
| Intel               | 3         | 3      | 3.16%   |
| Hitachi             | 3         | 3      | 3.16%   |
| Crucial             | 3         | 3      | 3.16%   |
| OCZ                 | 2         | 2      | 2.11%   |
| Micron Technology   | 2         | 2      | 2.11%   |
| Kingston            | 2         | 2      | 2.11%   |
| Gigabyte Technology | 2         | 2      | 2.11%   |
| Fujitsu             | 2         | 3      | 2.11%   |
| Transcend           | 1         | 1      | 1.05%   |
| SPCC                | 1         | 1      | 1.05%   |
| SK Hynix            | 1         | 2      | 1.05%   |
| PNY                 | 1         | 1      | 1.05%   |
| LITEONIT            | 1         | 1      | 1.05%   |
| KingDian            | 1         | 1      | 1.05%   |
| Intenso             | 1         | 1      | 1.05%   |
| HGST                | 1         | 1      | 1.05%   |
| Corsair             | 1         | 1      | 1.05%   |
| ASUSTek Computer    | 1         | 2      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 3         | 3.03%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 2.02%   |
| Seagate ST95005620AS 500GB                | 2         | 2.02%   |
| SanDisk SSD U100 24GB                     | 2         | 2.02%   |
| SanDisk pSSD 256GB                        | 2         | 2.02%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 2.02%   |
| Apple SSD SM0512F 500GB                   | 2         | 2.02%   |
| WDC WDS240G2G0A-00JH30 240GB              | 1         | 1.01%   |
| WDC WDS120G2G0B-00EPW0 120GB              | 1         | 1.01%   |
| WDC WDS120G1G0A-00SS50 120GB              | 1         | 1.01%   |
| WDC WD7500BPKT-75PK4T0 752GB              | 1         | 1.01%   |
| WDC WD3200BEVT-75ZCT2 320GB               | 1         | 1.01%   |
| WDC WD3200BEKT-60PVMT0 320GB              | 1         | 1.01%   |
| WDC WD2500LPCX-24C6HT0 250GB              | 1         | 1.01%   |
| WDC WD2500BEVT-80A23T0 250GB              | 1         | 1.01%   |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1.01%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1.01%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 1.01%   |
| WDC WD10SMRW-11Y43S0 1TB                  | 1         | 1.01%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.01%   |
| WDC WD10JPVX-60JC3T0 1TB                  | 1         | 1.01%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 1.01%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB        | 1         | 1.01%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB      | 1         | 1.01%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB      | 1         | 1.01%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1         | 1.01%   |
| Transcend TS512GSSD370S 512GB             | 1         | 1.01%   |
| Toshiba TR200 240GB                       | 1         | 1.01%   |
| Toshiba THNSNC128GBSJ                     | 1         | 1.01%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 1.01%   |
| Toshiba MK7575GSX 752GB                   | 1         | 1.01%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.01%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB       | 1         | 1.01%   |
| SPCC Solid State Disk 240GB               | 1         | 1.01%   |
| SK Hynix SKHynix_HFS512GD9TNG-L5B0B 512GB | 1         | 1.01%   |
| Seagate ST9750423AS 752GB                 | 1         | 1.01%   |
| Seagate ST9500325AS 500GB                 | 1         | 1.01%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 1.01%   |
| Seagate ST500LM030-2E717D 500GB           | 1         | 1.01%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1.01%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1.01%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.01%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.01%   |
| SanDisk SD9SN8W-128G-1006 128GB           | 1         | 1.01%   |
| Samsung SSD PM810 2.5-inch 7mm 256GB      | 1         | 1.01%   |
| Samsung SSD 970 PRO 1TB                   | 1         | 1.01%   |
| Samsung SSD 970 EVO Plus 500GB            | 1         | 1.01%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 1.01%   |
| Samsung SSD 860 EVO 250GB                 | 1         | 1.01%   |
| Samsung SSD 850 PRO 512GB                 | 1         | 1.01%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 1.01%   |
| Samsung SSD 840 EVO 250GB                 | 1         | 1.01%   |
| Samsung PM981 NVMe 256GB                  | 1         | 1.01%   |
| Samsung MZVLB256HBHQ-000L7 256GB          | 1         | 1.01%   |
| Samsung MZVLB256HBHQ-000L2 256GB          | 1         | 1.01%   |
| Samsung MZVLB256HAHQ-00000 256GB          | 1         | 1.01%   |
| Samsung MZVKW512HMJP-000H1 512GB          | 1         | 1.01%   |
| Samsung MZNLN256HCHP-000L7 256GB          | 1         | 1.01%   |
| Samsung MZMTD256HAGM-000L1 256GB          | 1         | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 12        | 12     | 31.58%  |
| Seagate | 11        | 12     | 28.95%  |
| Toshiba | 8         | 8      | 21.05%  |
| Hitachi | 3         | 3      | 7.89%   |
| Fujitsu | 2         | 3      | 5.26%   |
| HGST    | 1         | 1      | 2.63%   |
| Apple   | 1         | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 22.22%  |
| SanDisk             | 5         | 5      | 11.11%  |
| Apple               | 4         | 5      | 8.89%   |
| Toshiba             | 3         | 3      | 6.67%   |
| Intel               | 3         | 3      | 6.67%   |
| WDC                 | 2         | 3      | 4.44%   |
| OCZ                 | 2         | 2      | 4.44%   |
| Micron Technology   | 2         | 2      | 4.44%   |
| Kingston            | 2         | 2      | 4.44%   |
| Gigabyte Technology | 2         | 2      | 4.44%   |
| Crucial             | 2         | 2      | 4.44%   |
| Transcend           | 1         | 1      | 2.22%   |
| SPCC                | 1         | 1      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| LITEONIT            | 1         | 1      | 2.22%   |
| KingDian            | 1         | 1      | 2.22%   |
| Intenso             | 1         | 1      | 2.22%   |
| Corsair             | 1         | 1      | 2.22%   |
| ASUSTek Computer    | 1         | 2      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 42        | 50     | 45.16%  |
| HDD  | 38        | 40     | 40.86%  |
| NVMe | 13        | 16     | 13.98%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 90     | 85.06%  |
| NVMe | 13        | 16     | 14.94%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 69     | 74.03%  |
| 0.51-1.0   | 19        | 20     | 24.68%  |
| 1.01-2.0   | 1         | 1      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 74        | 84.09%  |
| 101-250    | 6         | 6.82%   |
| 51-100     | 3         | 3.41%   |
| 251-500    | 2         | 2.27%   |
| 21-50      | 2         | 2.27%   |
| 501-1000   | 1         | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 86        | 96.63%  |
| 21-50   | 2         | 2.25%   |
| 51-100  | 1         | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 5.26%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 5.26%   |
| WDC WD1200BEVS-07LAT0 120GB                      | 1         | 1      | 5.26%   |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 1      | 5.26%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 5.26%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 5.26%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 5.26%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 5.26%   |
| SanDisk SD9SN8W-128G-1006 128GB                  | 1         | 1      | 5.26%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 5.26%   |
| Intel SSDSC2CW060A3 64GB                         | 1         | 1      | 5.26%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 5.26%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 5.26%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 5.26%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 26.32%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Seagate             | 3         | 3      | 15.79%  |
| Hitachi             | 2         | 2      | 10.53%  |
| SanDisk             | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Corsair             | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 35.71%  |
| Toshiba | 3         | 3      | 21.43%  |
| Seagate | 3         | 3      | 21.43%  |
| Hitachi | 2         | 2      | 14.29%  |
| HGST    | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 73.68%  |
| SSD  | 5         | 5      | 26.32%  |

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
| Works    | 67        | 85     | 77.01%  |
| Malfunc  | 19        | 19     | 21.84%  |
| Detected | 1         | 2      | 1.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 68        | 68.69%  |
| Samsung Electronics              | 11        | 11.11%  |
| AMD                              | 11        | 11.11%  |
| Sandisk                          | 4         | 4.04%   |
| VIA Technologies                 | 1         | 1.01%   |
| SK Hynix                         | 1         | 1.01%   |
| Silicon Integrated Systems [SiS] | 1         | 1.01%   |
| Micron/Crucial Technology        | 1         | 1.01%   |
| JMicron Technology               | 1         | 1.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 10        | 9.26%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 10        | 9.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 7         | 6.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 5.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 5.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 4.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 2.78%   |
| Samsung SM951 AHCI                                                                     | 2         | 1.85%   |
| Samsung Apple PCIe SSD                                                                 | 2         | 1.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 2         | 1.85%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 1.85%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.85%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.93%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 1         | 0.93%   |
| SK Hynix hynix unknown                                                                 | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.93%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 0.93%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.93%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.93%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.93%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 0.93%   |
| JMicron JMB360 AHCI Controller                                                         | 1         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.93%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                                   | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.93%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 0.93%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.93%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 66        | 66%     |
| IDE  | 14        | 14%     |
| NVMe | 13        | 13%     |
| RAID | 7         | 7%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 87.64%  |
| AMD    | 11        | 12.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 4.49%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 3         | 3.37%   |
| Intel CPU Version                           | 2         | 2.25%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 2.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 2.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 2.25%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 2.25%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 2.25%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2.25%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 1.12%   |
| Intel Pentium III                           | 1         | 1.12%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.12%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.12%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 1.12%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 1.12%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 1.12%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.12%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.12%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.12%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz          | 1         | 1.12%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 1.12%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz          | 1         | 1.12%   |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 1.12%   |
| Intel Core i7-4610M CPU @ 3.00GHz           | 1         | 1.12%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.12%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i7-4500U CPU                     | 1         | 1.12%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.12%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.12%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.12%   |
| Intel Core i7 CPU L 640 @ 2.13GHz           | 1         | 1.12%   |
| Intel Core i5-9300HF CPU @ 2.40GHz          | 1         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.12%   |
| Intel Core i5-5350U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.12%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.12%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.12%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.12%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.12%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.12%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 1.12%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.12%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.12%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.12%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.12%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.12%   |
| Intel Core 2 Duo                            | 1         | 1.12%   |
| Intel Core 2 CPU T7200                      | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 27        | 30.34%  |
| Intel Core i7     | 23        | 25.84%  |
| Intel Core i3     | 6         | 6.74%   |
| Other             | 4         | 4.49%   |
| Intel Core 2 Duo  | 4         | 4.49%   |
| Intel Pentium     | 3         | 3.37%   |
| Intel Atom        | 3         | 3.37%   |
| AMD A6            | 3         | 3.37%   |
| Intel Celeron     | 2         | 2.25%   |
| AMD Ryzen 7       | 2         | 2.25%   |
| AMD A8            | 2         | 2.25%   |
| Intel Xeon        | 1         | 1.12%   |
| Intel Pentium III | 1         | 1.12%   |
| Intel Genuine     | 1         | 1.12%   |
| Intel Core m5     | 1         | 1.12%   |
| Intel Core i9     | 1         | 1.12%   |
| Intel Core 2      | 1         | 1.12%   |
| Intel Celeron M   | 1         | 1.12%   |
| AMD Ryzen 5       | 1         | 1.12%   |
| AMD E1            | 1         | 1.12%   |
| AMD A10           | 1         | 1.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 47        | 52.81%  |
| 4       | 26        | 29.21%  |
| Unknown | 8         | 8.99%   |
| 8       | 3         | 3.37%   |
| 1       | 3         | 3.37%   |
| 6       | 2         | 2.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 88        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 59        | 66.29%  |
| 1       | 20        | 22.47%  |
| Unknown | 10        | 11.24%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 16.85%  |
| Haswell       | 15        | 16.85%  |
| Skylake       | 11        | 12.36%  |
| IvyBridge     | 8         | 8.99%   |
| SandyBridge   | 6         | 6.74%   |
| Penryn        | 5         | 5.62%   |
| Puma          | 4         | 4.49%   |
| Bonnell       | 4         | 4.49%   |
| Zen+          | 3         | 3.37%   |
| Core          | 3         | 3.37%   |
| Broadwell     | 3         | 3.37%   |
| Westmere      | 2         | 2.25%   |
| Silvermont    | 2         | 2.25%   |
| P6            | 2         | 2.25%   |
| Steamroller   | 1         | 1.12%   |
| K10 Llano     | 1         | 1.12%   |
| Jaguar        | 1         | 1.12%   |
| Goldmont plus | 1         | 1.12%   |
| Excavator     | 1         | 1.12%   |
| CometLake     | 1         | 1.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 65        | 65.66%  |
| AMD              | 18        | 18.18%  |
| Nvidia           | 14        | 14.14%  |
| VIA Technologies | 1         | 1.01%   |
| S3 Graphics      | 1         | 1.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 8.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 7.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 6.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 3.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.91%   |
| Intel HD Graphics 620                                                                    | 3         | 2.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.91%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 2.91%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.94%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.94%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.97%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.97%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.97%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.97%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.97%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.97%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.97%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.97%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.97%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 0.97%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.97%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.97%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.97%   |
| Intel HD Graphics P530                                                                   | 1         | 0.97%   |
| Intel HD Graphics 630                                                                    | 1         | 0.97%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.97%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.97%   |
| Intel HD Graphics 530                                                                    | 1         | 0.97%   |
| Intel HD Graphics 515                                                                    | 1         | 0.97%   |
| Intel HD Graphics                                                                        | 1         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.97%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.97%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 1         | 0.97%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.97%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.97%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.97%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 0.97%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 0.97%   |
| AMD RV610/M72-S [Mobility Radeon HD 2400]                                                | 1         | 0.97%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 0.97%   |
| AMD Kaveri [Radeon R6 Graphics]                                                          | 1         | 0.97%   |
| AMD Baffin [Radeon Pro WX 4130/4150]                                                     | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 49        | 55.06%  |
| 1 x AMD         | 15        | 16.85%  |
| 2 x Intel       | 7         | 7.87%   |
| Intel + Nvidia  | 7         | 7.87%   |
| 1 x Nvidia      | 6         | 6.74%   |
| Intel + AMD     | 2         | 2.25%   |
| 1 x VIA         | 1         | 1.12%   |
| 1 x S3 Graphics | 1         | 1.12%   |
| AMD + Nvidia    | 1         | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 73        | 82.95%  |
| Unknown     | 12        | 13.64%  |
| Proprietary | 3         | 3.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 85.39%  |
| 0.01-0.5   | 6         | 6.74%   |
| 0.51-1.0   | 4         | 4.49%   |
| 1.01-2.0   | 3         | 3.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 13        | 17.33%  |
| AU Optronics            | 13        | 17.33%  |
| BOE                     | 11        | 14.67%  |
| Samsung Electronics     | 9         | 12%     |
| Chimei Innolux          | 6         | 8%      |
| Sharp                   | 3         | 4%      |
| Lenovo                  | 3         | 4%      |
| Chi Mei Optoelectronics | 3         | 4%      |
| Apple                   | 3         | 4%      |
| Panasonic               | 2         | 2.67%   |
| HannStar                | 2         | 2.67%   |
| LG Philips              | 1         | 1.33%   |
| Hewlett-Packard         | 1         | 1.33%   |
| Goldstar                | 1         | 1.33%   |
| CPT                     | 1         | 1.33%   |
| BenQ                    | 1         | 1.33%   |
| AOC                     | 1         | 1.33%   |
| Acer                    | 1         | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch              | 2         | 2.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch               | 2         | 2.63%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                 | 2         | 2.63%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                      | 2         | 2.63%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch             | 2         | 2.63%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch             | 2         | 2.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch             | 2         | 2.63%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                   | 1         | 1.32%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                   | 1         | 1.32%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                   | 1         | 1.32%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch       | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch      | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch      | 1         | 1.32%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch               | 1         | 1.32%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch               | 1         | 1.32%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                   | 1         | 1.32%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                   | 1         | 1.32%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                   | 1         | 1.32%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch                | 1         | 1.32%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 1         | 1.32%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch           | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch           | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch           | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 310x170mm 13.9-inch           | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 380x210mm 17.1-inch | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch  | 1         | 1.32%   |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                     | 1         | 1.32%   |
| BOE LCD Monitor BOE07E8 1366x768 310x170mm 13.9-inch                      | 1         | 1.32%   |
| BOE LCD Monitor BOE070D 1366x768 310x170mm 13.9-inch                      | 1         | 1.32%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                      | 1         | 1.32%   |
| BOE LCD Monitor BOE069B 1600x900 380x210mm 17.1-inch                      | 1         | 1.32%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                     | 1         | 1.32%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                     | 1         | 1.32%   |
| BOE LCD Monitor BOE062B 1920x1080 340x190mm 15.3-inch                     | 1         | 1.32%   |
| BOE LCD Monitor BOE05F5 1366x768 280x160mm 12.7-inch                      | 1         | 1.32%   |
| BenQ FP71V+ BNQ76A1 1280x1024 340x270mm 17.1-inch                         | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 340x190mm 15.3-inch             | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch             | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch            | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO233E 1600x900 310x170mm 13.9-inch             | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 31        | 41.33%  |
| 1920x1080 (FHD)  | 20        | 26.67%  |
| 1600x900 (HD+)   | 5         | 6.67%   |
| 1280x800 (WXGA)  | 4         | 5.33%   |
| 1024x600         | 4         | 5.33%   |
| 1440x900 (WXGA+) | 3         | 4%      |
| 3840x2160 (4K)   | 2         | 2.67%   |
| 2880x1620        | 2         | 2.67%   |
| 3200x1800 (QHD+) | 1         | 1.33%   |
| 2880x1800        | 1         | 1.33%   |
| 2560x1440 (QHD)  | 1         | 1.33%   |
| 1280x1024 (SXGA) | 1         | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 32        | 42.11%  |
| 13     | 17        | 22.37%  |
| 17     | 7         | 9.21%   |
| 12     | 7         | 9.21%   |
| 10     | 4         | 5.26%   |
| 24     | 3         | 3.95%   |
| 27     | 2         | 2.63%   |
| 11     | 2         | 2.63%   |
| 18     | 1         | 1.32%   |
| 14     | 1         | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 56.58%  |
| 201-300     | 21        | 27.63%  |
| 351-400     | 6         | 7.89%   |
| 501-600     | 4         | 5.26%   |
| 601-700     | 1         | 1.32%   |
| 401-500     | 1         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 61        | 87.14%  |
| 16/10 | 8         | 11.43%  |
| 5/4   | 1         | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 25        | 32.89%  |
| 81-90          | 13        | 17.11%  |
| 61-70          | 7         | 9.21%   |
| 101-110        | 7         | 9.21%   |
| 71-80          | 5         | 6.58%   |
| 121-130        | 5         | 6.58%   |
| 41-50          | 4         | 5.26%   |
| 201-250        | 3         | 3.95%   |
| 51-60          | 2         | 2.63%   |
| 301-350        | 2         | 2.63%   |
| 141-150        | 2         | 2.63%   |
| 131-140        | 1         | 1.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 33        | 44%     |
| 121-160       | 22        | 29.33%  |
| 161-240       | 9         | 12%     |
| 51-100        | 9         | 12%     |
| More than 240 | 2         | 2.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 70        | 77.78%  |
| 0     | 16        | 17.78%  |
| 2     | 3         | 3.33%   |
| 3     | 1         | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 51        | 38.64%  |
| Realtek Semiconductor             | 34        | 25.76%  |
| Qualcomm Atheros                  | 24        | 18.18%  |
| Broadcom                          | 8         | 6.06%   |
| Ralink                            | 3         | 2.27%   |
| Marvell Technology Group          | 2         | 1.52%   |
| VIA Technologies                  | 1         | 0.76%   |
| TP-Link                           | 1         | 0.76%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.76%   |
| Sierra Wireless                   | 1         | 0.76%   |
| Samsung Electronics               | 1         | 0.76%   |
| Qualcomm                          | 1         | 0.76%   |
| JMicron Technology                | 1         | 0.76%   |
| Fibocom                           | 1         | 0.76%   |
| Ericsson Business Mobile Networks | 1         | 0.76%   |
| Atheros                           | 1         | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 11.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 6.74%   |
| Intel Wireless 7260                                               | 9         | 5.06%   |
| Intel Wireless 8260                                               | 6         | 3.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.81%   |
| Intel Wireless 3165                                               | 5         | 2.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.25%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.69%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.69%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.69%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.69%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 1.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.12%   |
| Intel Wireless 7265                                               | 2         | 1.12%   |
| Intel WiFi Link 5100                                              | 2         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.12%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.12%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.56%   |
| Sierra Wireless EM7455                                            | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.56%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.56%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.56%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.56%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.56%   |
| Intel Wireless-AC 9260                                            | 1         | 0.56%   |
| Intel WiMAX/WiFi Link 5150                                        | 1         | 0.56%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 0.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 52.17%  |
| Qualcomm Atheros      | 19        | 20.65%  |
| Realtek Semiconductor | 13        | 14.13%  |
| Broadcom              | 6         | 6.52%   |
| Ralink                | 3         | 3.26%   |
| TP-Link               | 1         | 1.09%   |
| Sierra Wireless       | 1         | 1.09%   |
| Atheros               | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                  | 9         | 9.47%   |
| Intel Wireless 8260                                                  | 6         | 6.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 5.26%   |
| Intel Wireless 3165                                                  | 5         | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 4.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 3.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3         | 3.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 3.16%   |
| Intel Wireless 8265 / 8275                                           | 3         | 3.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 3.16%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 3         | 3.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 2.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 2.11%   |
| Intel Wireless 7265                                                  | 2         | 2.11%   |
| Intel WiFi Link 5100                                                 | 2         | 2.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 2         | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 2.11%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 2.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 1.05%   |
| Sierra Wireless EM7455                                               | 1         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.05%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.05%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                | 1         | 1.05%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1         | 1.05%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1         | 1.05%   |
| Intel Wireless-AC 9260                                               | 1         | 1.05%   |
| Intel WiMAX/WiFi Link 5150                                           | 1         | 1.05%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.05%   |
| Intel Centrino Wireless-N 6150                                       | 1         | 1.05%   |
| Intel Centrino Wireless-N 135                                        | 1         | 1.05%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 1.05%   |
| Intel Centrino WiMAX 6150                                            | 1         | 1.05%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.05%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 1         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 1.05%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller  | 1         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.05%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 33        | 41.25%  |
| Intel                            | 28        | 35%     |
| Qualcomm Atheros                 | 7         | 8.75%   |
| Broadcom                         | 5         | 6.25%   |
| Marvell Technology Group         | 2         | 2.5%    |
| VIA Technologies                 | 1         | 1.25%   |
| Silicon Integrated Systems [SiS] | 1         | 1.25%   |
| Samsung Electronics              | 1         | 1.25%   |
| Qualcomm                         | 1         | 1.25%   |
| JMicron Technology               | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 25.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 14.81%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 4.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 4.94%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 3.7%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.7%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 3.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.47%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.47%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.23%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.23%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 1.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.23%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.23%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.23%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.23%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.23%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.23%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 1.23%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.23%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.23%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 87        | 52.1%   |
| Ethernet | 78        | 46.71%  |
| Unknown  | 2         | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 72        | 50.7%   |
| WiFi     | 68        | 47.89%  |
| Unknown  | 2         | 1.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 78        | 87.64%  |
| 1     | 11        | 12.36%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 80        | 89.89%  |
| Yes  | 9         | 10.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 43.75%  |
| Realtek Semiconductor           | 5         | 7.81%   |
| Qualcomm Atheros Communications | 5         | 7.81%   |
| Lite-On Technology              | 5         | 7.81%   |
| Broadcom                        | 4         | 6.25%   |
| ASUSTek Computer                | 4         | 6.25%   |
| Apple                           | 4         | 6.25%   |
| IMC Networks                    | 3         | 4.69%   |
| Foxconn / Hon Hai               | 2         | 3.13%   |
| Hewlett-Packard                 | 1         | 1.56%   |
| Dell                            | 1         | 1.56%   |
| Cambridge Silicon Radio         | 1         | 1.56%   |
| Alps Electric                   | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 29.69%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 4.69%   |
| Intel AX201 Bluetooth                                       | 3         | 4.69%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 3.13%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 3.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.13%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 3.13%   |
| Apple Bluetooth Host Controller                             | 2         | 3.13%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 3.13%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.56%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.56%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.56%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.56%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.56%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.56%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.56%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device        | 1         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.56%   |
| Lite-On Bluetooth USB Module                                | 1         | 1.56%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.56%   |
| Intel AX200 Bluetooth                                       | 1         | 1.56%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.56%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.56%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.56%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.56%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.56%   |
| ASUS ASUS USB-BT500                                         | 1         | 1.56%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 75        | 75.76%  |
| AMD                              | 15        | 15.15%  |
| Nvidia                           | 5         | 5.05%   |
| VIA Technologies                 | 1         | 1.01%   |
| Silicon Integrated Systems [SiS] | 1         | 1.01%   |
| Realtek Semiconductor            | 1         | 1.01%   |
| Blue Microphones                 | 1         | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 11.02%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 7.09%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 7.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 6.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 5.51%   |
| AMD FCH Azalia Controller                                                                         | 7         | 5.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 4.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 3.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 3.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 3.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.36%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.36%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.36%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.57%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.57%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.79%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 1         | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.79%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.79%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.79%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.79%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.79%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.79%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.79%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.79%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.79%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 31.43%  |
| SK Hynix            | 26        | 24.76%  |
| Unknown             | 10        | 9.52%   |
| Micron Technology   | 10        | 9.52%   |
| Kingston            | 5         | 4.76%   |
| Elpida              | 4         | 3.81%   |
| Crucial             | 4         | 3.81%   |
| Transcend           | 2         | 1.9%    |
| A-DATA Technology   | 2         | 1.9%    |
| Unknown             | 2         | 1.9%    |
| Unknown (ABCD)      | 1         | 0.95%   |
| Unknown (09D5)      | 1         | 0.95%   |
| Nanya Technology    | 1         | 0.95%   |
| Magnum Tech         | 1         | 0.95%   |
| G.Skill             | 1         | 0.95%   |
| Corsair             | 1         | 0.95%   |
| 48spaces            | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 7         | 6.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 3.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 2.61%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 2.61%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 2.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s               | 3         | 2.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 2.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.74%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.74%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 2         | 1.74%   |
| Unknown                                                             | 2         | 1.74%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                           | 1         | 0.87%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                           | 1         | 0.87%   |
| Unknown RAM Module 512MB SODIMM SDRAM                               | 1         | 0.87%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.87%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                              | 1         | 0.87%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                          | 1         | 0.87%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.87%   |
| Unknown RAM Module 128MB SODIMM SDRAM                               | 1         | 0.87%   |
| Unknown RAM Module 1024MB SODIMM RAM                                | 1         | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB SODIMM LPDDR4 2133MT/s | 1         | 0.87%   |
| Unknown (09D5) RAM Module 16GB SODIMM DDR4 2400MT/s                 | 1         | 0.87%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                      | 1         | 0.87%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s                    | 1         | 0.87%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.87%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s                | 1         | 0.87%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s               | 1         | 0.87%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.87%   |
| SK Hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.87%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s             | 1         | 0.87%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.87%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.87%   |
| SK Hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s       | 1         | 0.87%   |
| SK Hynix RAM H5TC8G63AMR-PBA 4096MB 1600MT/s                        | 1         | 0.87%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s                        | 1         | 0.87%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5273DH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.87%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.87%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 0.87%   |
| Samsung RAM M08GD04P1600C1 8192MB SODIMM DDR3 1333MT/s              | 1         | 0.87%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s              | 1         | 0.87%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 44        | 49.44%  |
| DDR4    | 25        | 28.09%  |
| DDR2    | 8         | 8.99%   |
| SDRAM   | 3         | 3.37%   |
| LPDDR3  | 3         | 3.37%   |
| Unknown | 2         | 2.25%   |
| RAM     | 1         | 1.12%   |
| LPDDR4  | 1         | 1.12%   |
| DRAM    | 1         | 1.12%   |
| DDR     | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 85        | 94.44%  |
| Chip    | 3         | 3.33%   |
| Unknown | 2         | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 44        | 42.72%  |
| 8192  | 28        | 27.18%  |
| 2048  | 16        | 15.53%  |
| 16384 | 8         | 7.77%   |
| 1024  | 4         | 3.88%   |
| 32768 | 1         | 0.97%   |
| 512   | 1         | 0.97%   |
| 128   | 1         | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 34        | 35.79%  |
| 2400    | 11        | 11.58%  |
| 2667    | 10        | 10.53%  |
| 2133    | 7         | 7.37%   |
| 1334    | 6         | 6.32%   |
| 667     | 6         | 6.32%   |
| 1333    | 5         | 5.26%   |
| Unknown | 5         | 5.26%   |
| 3200    | 3         | 3.16%   |
| 1867    | 2         | 2.11%   |
| 800     | 2         | 2.11%   |
| 1866    | 1         | 1.05%   |
| 1067    | 1         | 1.05%   |
| 975     | 1         | 1.05%   |
| 533     | 1         | 1.05%   |

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
| Chicony Electronics                    | 17        | 24.64%  |
| Acer                                   | 9         | 13.04%  |
| Sunplus Innovation Technology          | 7         | 10.14%  |
| Realtek Semiconductor                  | 7         | 10.14%  |
| Suyin                                  | 6         | 8.7%    |
| Microdia                               | 5         | 7.25%   |
| Silicon Motion                         | 3         | 4.35%   |
| IMC Networks                           | 3         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.35%   |
| Quanta                                 | 2         | 2.9%    |
| Lite-On Technology                     | 2         | 2.9%    |
| Logitech                               | 1         | 1.45%   |
| Intel                                  | 1         | 1.45%   |
| Genesys Logic                          | 1         | 1.45%   |
| Apple                                  | 1         | 1.45%   |
| Alcor Micro                            | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 6         | 8.7%    |
| Acer Integrated Camera                                         | 5         | 7.25%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 5.8%    |
| Suyin Acer Crystal Eye webcam                                  | 2         | 2.9%    |
| Realtek Realtek USB2.0 PC Camera                               | 2         | 2.9%    |
| Microdia Integrated_Webcam_HD                                  | 2         | 2.9%    |
| Microdia Integrated Webcam                                     | 2         | 2.9%    |
| Chicony HD WebCam                                              | 2         | 2.9%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 2         | 2.9%    |
| Suyin USB 2.0 UVC 1.3M WebCam                                  | 1         | 1.45%   |
| Suyin Laptop_Integrated_Webcam_3M                              | 1         | 1.45%   |
| Suyin HD WebCam                                                | 1         | 1.45%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 1.45%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.45%   |
| Sunplus Integrated Webcam                                      | 1         | 1.45%   |
| Sunplus Asus Webcam                                            | 1         | 1.45%   |
| Silicon Motion WebCam SCX Series                               | 1         | 1.45%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 1.45%   |
| Silicon Motion 300k Pixel Camera                               | 1         | 1.45%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 1         | 1.45%   |
| Realtek USB Camera                                             | 1         | 1.45%   |
| Realtek Lenovo EasyCamera                                      | 1         | 1.45%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.45%   |
| Realtek HD Webcam - Realtek                                    | 1         | 1.45%   |
| Quanta Realtek DMFT - RGB                                      | 1         | 1.45%   |
| Quanta Front camera                                            | 1         | 1.45%   |
| Microdia Sonix USB 2.0 Camera                                  | 1         | 1.45%   |
| Logitech HD Pro Webcam C920                                    | 1         | 1.45%   |
| Lite-On Integrated Camera                                      | 1         | 1.45%   |
| Lite-On HP Universal Camera                                    | 1         | 1.45%   |
| Intel WiMAX Connection 2400m                                   | 1         | 1.45%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 1.45%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.45%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.45%   |
| Genesys Logic Camera                                           | 1         | 1.45%   |
| Chicony Webcam                                                 | 1         | 1.45%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.45%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.45%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.45%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 1.45%   |
| Chicony HP TrueVision HD Camera                                | 1         | 1.45%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 1.45%   |
| Chicony FJ Camera                                              | 1         | 1.45%   |
| Chicony Chicony USB2.0 Camera                                  | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.45%   |
| Apple FaceTime HD Camera                                       | 1         | 1.45%   |
| Alcor Micro HP WebCam-101                                      | 1         | 1.45%   |
| Acer USB2.0 Camera                                             | 1         | 1.45%   |
| Acer NEC HD WebCam                                             | 1         | 1.45%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.45%   |
| Acer EasyCamera                                                | 1         | 1.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 10        | 66.67%  |
| Synaptics        | 2         | 13.33%  |
| Upek             | 1         | 6.67%   |
| Broadcom         | 1         | 6.67%   |
| AuthenTec        | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 20%     |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| AuthenTec AES1600                                                            | 1         | 6.67%   |
| Unknown                                                                      | 1         | 6.67%   |

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
| 1     | 29        | 31.87%  |
| 2     | 25        | 27.47%  |
| 3     | 14        | 15.38%  |
| 0     | 14        | 15.38%  |
| 4     | 6         | 6.59%   |
| 7     | 1         | 1.1%    |
| 6     | 1         | 1.1%    |
| 5     | 1         | 1.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 60        | 41.96%  |
| Net/wireless             | 25        | 17.48%  |
| Card reader              | 16        | 11.19%  |
| Bluetooth                | 16        | 11.19%  |
| Fingerprint reader       | 15        | 10.49%  |
| Firewire controller      | 8         | 5.59%   |
| Storage/raid             | 1         | 0.7%    |
| Sound                    | 1         | 0.7%    |
| Network                  | 1         | 0.7%    |

