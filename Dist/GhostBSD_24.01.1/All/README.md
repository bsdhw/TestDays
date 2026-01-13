GhostBSD 24.01.1 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for GhostBSD 24.01.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GhostBSD_24.01.1/Desktop/README.md) and [notebooks](/Dist/GhostBSD_24.01.1/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 54

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [8e2f33a68c](https://bsd-hardware.info/?probe=8e2f33a68c) | Mar 07, 2025 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [0243819ad2](https://bsd-hardware.info/?probe=0243819ad2) | Mar 07, 2025 |
| Lenovo        | ThinkCentre M715q 10M2S0... | Desktop     | [66a3b3e94e](https://bsd-hardware.info/?probe=66a3b3e94e) | Sep 02, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [9ae98f134a](https://bsd-hardware.info/?probe=9ae98f134a) | Aug 09, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [e123332fb8](https://bsd-hardware.info/?probe=e123332fb8) | May 16, 2024 |
| Dell          | 055H3G A01                  | Desktop     | [5d0cd53384](https://bsd-hardware.info/?probe=5d0cd53384) | May 16, 2024 |
| Biostar       | B450MH                      | Desktop     | [6fc7467762](https://bsd-hardware.info/?probe=6fc7467762) | May 13, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [d5f43a27aa](https://bsd-hardware.info/?probe=d5f43a27aa) | May 12, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [3c3432b2c0](https://bsd-hardware.info/?probe=3c3432b2c0) | May 11, 2024 |
| Infinix       | INBook X1                   | Notebook    | [847a9cb112](https://bsd-hardware.info/?probe=847a9cb112) | May 10, 2024 |
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
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3ccdd0084b](https://bsd-hardware.info/?probe=3ccdd0084b) | Apr 05, 2024 |
| Dell          | Latitude E5540              | Notebook    | [108e2acb98](https://bsd-hardware.info/?probe=108e2acb98) | Apr 01, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [56ea2c6719](https://bsd-hardware.info/?probe=56ea2c6719) | Apr 01, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [cfcf823cca](https://bsd-hardware.info/?probe=cfcf823cca) | Apr 01, 2024 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1010       | Desktop     | [4a359f1f86](https://bsd-hardware.info/?probe=4a359f1f86) | Apr 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| Lenovo        | 3743 NOK                    | Desktop     | [fd5dc51da2](https://bsd-hardware.info/?probe=fd5dc51da2) | Mar 31, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [db1d3cd098](https://bsd-hardware.info/?probe=db1d3cd098) | Mar 19, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [403a4f0ea9](https://bsd-hardware.info/?probe=403a4f0ea9) | Mar 17, 2024 |
| Google        | Cave                        | Notebook    | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| ASUSTek       | H61M-K                      | Desktop     | [1f6840c3f3](https://bsd-hardware.info/?probe=1f6840c3f3) | Mar 12, 2024 |
| LG Electro... | R590-P.BE54P1               | Desktop     | [120ec3afe6](https://bsd-hardware.info/?probe=120ec3afe6) | Mar 09, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [ac72a9a34a](https://bsd-hardware.info/?probe=ac72a9a34a) | Feb 23, 2024 |
| Dell          | Latitude E6540              | Notebook    | [92ba9b26e1](https://bsd-hardware.info/?probe=92ba9b26e1) | Feb 21, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [5392dc85bb](https://bsd-hardware.info/?probe=5392dc85bb) | Feb 21, 2024 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [39e4fb5eba](https://bsd-hardware.info/?probe=39e4fb5eba) | Feb 20, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [e933816d9f](https://bsd-hardware.info/?probe=e933816d9f) | Feb 19, 2024 |
| Biostar       | B450NH                      | Desktop     | [2db279db1d](https://bsd-hardware.info/?probe=2db279db1d) | Feb 16, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [fdeb2cee9d](https://bsd-hardware.info/?probe=fdeb2cee9d) | Feb 14, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Dell          | 0GDJXY A00                  | All in one  | [c7f489add0](https://bsd-hardware.info/?probe=c7f489add0) | Jan 28, 2024 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 43        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MATE | 35        | 81.4%   |
| XFCE | 4         | 9.3%    |
| KDE5 | 3         | 6.98%   |
| dwm  | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 43        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 42        | 97.67%  |
| SDDM    | 1         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 23        | 53.49%  |
| C       | 9         | 20.93%  |
| es_ES   | 4         | 9.3%    |
| de_DE   | 3         | 6.98%   |
| ru_RU   | 1         | 2.33%   |
| pt_BR   | 1         | 2.33%   |
| fr_FR   | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 83.72%  |
| BIOS | 7         | 16.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 40        | 93.02%  |
| Ufs  | 3         | 6.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 42        | 97.67%  |
| MBR  | 1         | 2.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 12        | 27.91%  |
| Lenovo              | 7         | 16.28%  |
| Hewlett-Packard     | 6         | 13.95%  |
| ASUSTek Computer    | 5         | 11.63%  |
| Gigabyte Technology | 2         | 4.65%   |
| TUXEDO              | 1         | 2.33%   |
| MSI                 | 1         | 2.33%   |
| LG Electronics      | 1         | 2.33%   |
| Infinix             | 1         | 2.33%   |
| HUAWEI              | 1         | 2.33%   |
| Google              | 1         | 2.33%   |
| F-Plus Mobile       | 1         | 2.33%   |
| Biostar             | 1         | 2.33%   |
| Apple               | 1         | 2.33%   |
| Alienware           | 1         | 2.33%   |
| Unknown             | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Dell XPS 13 9360                            | 2         | 4.65%   |
| TUXEDO Aura 15 Gen1                         | 1         | 2.33%   |
| MSI MS-7B24                                 | 1         | 2.33%   |
| LG R590-P.BE54P1                            | 1         | 2.33%   |
| Lenovo ThinkPad X240 20AMS3FY00             | 1         | 2.33%   |
| Lenovo ThinkPad X220 429135G                | 1         | 2.33%   |
| Lenovo ThinkPad W550s 20E2000QUS            | 1         | 2.33%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 2.33%   |
| Lenovo ThinkCentre M715q 10M2S08Y00         | 1         | 2.33%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ            | 1         | 2.33%   |
| Lenovo IdeaCentre Gaming5 14ACN6 90RW005PUL | 1         | 2.33%   |
| Infinix INBook X1                           | 1         | 2.33%   |
| HUAWEI PUM-WDX9                             | 1         | 2.33%   |
| HP ProLiant MicroServer Gen8                | 1         | 2.33%   |
| HP ProBook 645 G3                           | 1         | 2.33%   |
| HP ENVY x360 Convertible 15-ee1xxx          | 1         | 2.33%   |
| HP EliteBook 840 G6                         | 1         | 2.33%   |
| HP EliteBook 2560p                          | 1         | 2.33%   |
| HP 255 G8 Notebook PC                       | 1         | 2.33%   |
| Google Cave                                 | 1         | 2.33%   |
| Gigabyte P55-USB3                           | 1         | 2.33%   |
| Gigabyte GA-990FX-GAMING                    | 1         | 2.33%   |
| F-Plus Mobile FLAPTOP r                     | 1         | 2.33%   |
| Dell XPS 13 9305                            | 1         | 2.33%   |
| Dell Vostro 3350                            | 1         | 2.33%   |
| Dell OptiPlex 960                           | 1         | 2.33%   |
| Dell OptiPlex 7050                          | 1         | 2.33%   |
| Dell Latitude E6540                         | 1         | 2.33%   |
| Dell Latitude E5540                         | 1         | 2.33%   |
| Dell Latitude 7490                          | 1         | 2.33%   |
| Dell Latitude 7390                          | 1         | 2.33%   |
| Dell Inspiron 5559                          | 1         | 2.33%   |
| Dell Inspiron 5490 AIO                      | 1         | 2.33%   |
| Biostar B450MH                              | 1         | 2.33%   |
| ASUS X202E                                  | 1         | 2.33%   |
| ASUS ROG STRIX B550-F GAMING                | 1         | 2.33%   |
| ASUS Pro B560M-C                            | 1         | 2.33%   |
| ASUS PRIME Z390-A                           | 1         | 2.33%   |
| ASUS H61M-K                                 | 1         | 2.33%   |
| Apple MacPro5,1                             | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 9.3%    |
| Dell Latitude            | 4         | 9.3%    |
| Dell XPS                 | 3         | 6.98%   |
| HP EliteBook             | 2         | 4.65%   |
| Dell OptiPlex            | 2         | 4.65%   |
| Dell Inspiron            | 2         | 4.65%   |
| TUXEDO Aura              | 1         | 2.33%   |
| MSI MS-7B24              | 1         | 2.33%   |
| LG R590-P.BE54P1         | 1         | 2.33%   |
| Lenovo ThinkCentre       | 1         | 2.33%   |
| Lenovo Legion            | 1         | 2.33%   |
| Lenovo IdeaCentre        | 1         | 2.33%   |
| Infinix INBook           | 1         | 2.33%   |
| HUAWEI PUM-WDX9          | 1         | 2.33%   |
| HP ProLiant              | 1         | 2.33%   |
| HP ProBook               | 1         | 2.33%   |
| HP ENVY                  | 1         | 2.33%   |
| HP 255                   | 1         | 2.33%   |
| Google Cave              | 1         | 2.33%   |
| Gigabyte P55-USB3        | 1         | 2.33%   |
| Gigabyte GA-990FX-GAMING | 1         | 2.33%   |
| F-Plus Mobile FLAPTOP    | 1         | 2.33%   |
| Dell Vostro              | 1         | 2.33%   |
| Biostar B450MH           | 1         | 2.33%   |
| ASUS X202E               | 1         | 2.33%   |
| ASUS ROG                 | 1         | 2.33%   |
| ASUS Pro                 | 1         | 2.33%   |
| ASUS PRIME               | 1         | 2.33%   |
| ASUS H61M-K              | 1         | 2.33%   |
| Apple MacPro5            | 1         | 2.33%   |
| Alienware Area-51m       | 1         | 2.33%   |
| Unknown                  | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 7         | 16.28%  |
| 2020 | 6         | 13.95%  |
| 2023 | 5         | 11.63%  |
| 2013 | 5         | 11.63%  |
| 2022 | 4         | 9.3%    |
| 2018 | 3         | 6.98%   |
| 2011 | 3         | 6.98%   |
| 2019 | 2         | 4.65%   |
| 2016 | 2         | 4.65%   |
| 2015 | 2         | 4.65%   |
| 2017 | 1         | 2.33%   |
| 2014 | 1         | 2.33%   |
| 2012 | 1         | 2.33%   |
| 2010 | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 25        | 58.14%  |
| Desktop     | 16        | 37.21%  |
| Convertible | 1         | 2.33%   |
| All in one  | 1         | 2.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 97.67%  |
| Yes  | 1         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 17        | 39.53%  |
| 8.01-16.0   | 17        | 39.53%  |
| 4.01-8.0    | 3         | 6.98%   |
| 32.01-64.0  | 3         | 6.98%   |
| 64.01-256.0 | 3         | 6.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 20        | 46.51%  |
| 0.01-0.5 | 10        | 23.26%  |
| 1.01-2.0 | 9         | 20.93%  |
| 2.01-3.0 | 4         | 9.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 46.51%  |
| 0      | 15        | 34.88%  |
| 2      | 6         | 13.95%  |
| 4      | 1         | 2.33%   |
| 3      | 1         | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 81.4%   |
| Yes       | 8         | 18.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 79.07%  |
| No        | 9         | 20.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 79.07%  |
| No        | 9         | 20.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 67.44%  |
| No        | 14        | 32.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 12        | 27.91%  |
| Germany                | 5         | 11.63%  |
| Denmark                | 4         | 9.3%    |
| Paraguay               | 3         | 6.98%   |
| Bulgaria               | 3         | 6.98%   |
| Spain                  | 2         | 4.65%   |
| France                 | 2         | 4.65%   |
| Canada                 | 2         | 4.65%   |
| Switzerland            | 1         | 2.33%   |
| Russia                 | 1         | 2.33%   |
| Peru                   | 1         | 2.33%   |
| Lithuania              | 1         | 2.33%   |
| Indonesia              | 1         | 2.33%   |
| Cuba                   | 1         | 2.33%   |
| Brazil                 | 1         | 2.33%   |
| Bosnia and Herzegovina | 1         | 2.33%   |
| Austria                | 1         | 2.33%   |
| Argentina              | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Frederiksberg               | 4         | 9.3%    |
| Victoria                    | 2         | 4.65%   |
| Tucson                      | 2         | 4.65%   |
| Sofia                       | 2         | 4.65%   |
| Roslindale                  | 2         | 4.65%   |
| Asunción                   | 2         | 4.65%   |
| Zurich                      | 1         | 2.33%   |
| Voskresensk                 | 1         | 2.33%   |
| Vienna                      | 1         | 2.33%   |
| Valencia                    | 1         | 2.33%   |
| Tsarevo                     | 1         | 2.33%   |
| Stuttgart                   | 1         | 2.33%   |
| Solden                      | 1         | 2.33%   |
| Sarajevo                    | 1         | 2.33%   |
| San Nicolás de los Arroyos | 1         | 2.33%   |
| San Lorenzo                 | 1         | 2.33%   |
| San Jose                    | 1         | 2.33%   |
| Redondela                   | 1         | 2.33%   |
| Pacoima                     | 1         | 2.33%   |
| Navalcarnero                | 1         | 2.33%   |
| Munich                      | 1         | 2.33%   |
| Lima                        | 1         | 2.33%   |
| Leutkirch                   | 1         | 2.33%   |
| Leitchfield                 | 1         | 2.33%   |
| Jonava                      | 1         | 2.33%   |
| Jakarta                     | 1         | 2.33%   |
| Jacksonville                | 1         | 2.33%   |
| Havana                      | 1         | 2.33%   |
| Hamburg                     | 1         | 2.33%   |
| Fos-sur-Mer                 | 1         | 2.33%   |
| Eureka                      | 1         | 2.33%   |
| Embu                        | 1         | 2.33%   |
| Colombes                    | 1         | 2.33%   |
| Bothell                     | 1         | 2.33%   |
| Atlanta                     | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 21.05%  |
| Samsung Electronics | 6         | 6      | 15.79%  |
| Toshiba             | 4         | 4      | 10.53%  |
| Crucial             | 4         | 4      | 10.53%  |
| WDC                 | 3         | 3      | 7.89%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Intel               | 2         | 2      | 5.26%   |
| XrayDisk            | 1         | 1      | 2.63%   |
| Team                | 1         | 1      | 2.63%   |
| ShiJi               | 1         | 1      | 2.63%   |
| LITEONIT            | 1         | 1      | 2.63%   |
| Intenso             | 1         | 1      | 2.63%   |
| Hitachi             | 1         | 1      | 2.63%   |
| Fanxiang            | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba DT01ACA050 500GB             | 2         | 5.13%   |
| Seagate ST1000VM002-1SD102 1TB       | 2         | 5.13%   |
| Samsung SSD 870 EVO 500GB            | 2         | 5.13%   |
| Samsung HM320JI 320GB                | 2         | 5.13%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 5.13%   |
| XrayDisk 1TB SSD                     | 1         | 2.56%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 2.56%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 2.56%   |
| WDC WD20EZBX-08AYR 2TB               | 1         | 2.56%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB | 1         | 2.56%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB  | 1         | 2.56%   |
| Team T253X1240G 240GB                | 1         | 2.56%   |
| ShiJi SSD 512GB                      | 1         | 2.56%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 2.56%   |
| Seagate ST4000VN008-2DR166 4TB       | 1         | 2.56%   |
| Seagate ST380815AS 80GB              | 1         | 2.56%   |
| Seagate ST3500418AS 500GB            | 1         | 2.56%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 2.56%   |
| Seagate ST1000DM003-1CH162 1TB       | 1         | 2.56%   |
| SanDisk SD9SN8W-256G-1016 256GB      | 1         | 2.56%   |
| SanDisk SD8TB8U512G1001 512GB        | 1         | 2.56%   |
| Samsung SSD 860 PRO 512GB            | 1         | 2.56%   |
| Samsung SSD 830 Series 256GB         | 1         | 2.56%   |
| LITEONIT LCS-128M6S 128GB            | 1         | 2.56%   |
| Intenso SSD 256GB                    | 1         | 2.56%   |
| Intel SSDSCKKF512G8 SATA 512GB       | 1         | 2.56%   |
| Intel SSDSA2BW160G3H 160GB           | 1         | 2.56%   |
| Hitachi HDS721616PLA380 160GB        | 1         | 2.56%   |
| Fanxiang S101 512GB                  | 1         | 2.56%   |
| Crucial CT240BX500SSD1 240GB         | 1         | 2.56%   |
| Crucial CT2000BX500SSD1 2TB          | 1         | 2.56%   |
| China SATA SSD 120GB                 | 1         | 2.56%   |
| Apple SSD SM0128G 121GB              | 1         | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 57.14%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 16.67%  |
| Crucial             | 4         | 4      | 16.67%  |
| WDC                 | 2         | 2      | 8.33%   |
| Toshiba             | 2         | 2      | 8.33%   |
| SanDisk             | 2         | 2      | 8.33%   |
| Intel               | 2         | 2      | 8.33%   |
| XrayDisk            | 1         | 1      | 4.17%   |
| Team                | 1         | 1      | 4.17%   |
| ShiJi               | 1         | 1      | 4.17%   |
| LITEONIT            | 1         | 1      | 4.17%   |
| Intenso             | 1         | 1      | 4.17%   |
| Fanxiang            | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 24     | 70.97%  |
| HDD  | 9         | 15     | 29.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 39     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 23     | 52.94%  |
| 0.51-1.0   | 11        | 11     | 32.35%  |
| 1.01-2.0   | 4         | 4      | 11.76%  |
| 3.01-4.0   | 1         | 1      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 27.91%  |
| 251-500    | 10        | 23.26%  |
| 1-20       | 6         | 13.95%  |
| 21-50      | 5         | 11.63%  |
| 501-1000   | 4         | 9.3%    |
| Unknown    | 3         | 6.98%   |
| 51-100     | 2         | 4.65%   |
| 1001-2000  | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 35        | 81.4%   |
| 21-50   | 4         | 9.3%    |
| Unknown | 3         | 6.98%   |
| 101-250 | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics HM320JI 320GB     | 2         | 2      | 25%     |
| Toshiba THNSNK128GVN8 M.2 2280 128GB  | 1         | 1      | 12.5%   |
| ShiJi SSD 512GB                       | 1         | 1      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 12.5%   |
| Hitachi HDS721616PLA380 160GB         | 1         | 1      | 12.5%   |
| Fanxiang S101 512GB                   | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 37.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| ShiJi               | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |
| Fanxiang            | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| Seagate             | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 4      | 57.14%  |
| HDD  | 3         | 4      | 42.86%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Intel SSDSCKKF512G8 SATA 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 24        | 30     | 77.42%  |
| Malfunc | 6         | 8      | 19.35%  |
| Failed  | 1         | 1      | 3.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 27        | 45%     |
| AMD                          | 11        | 18.33%  |
| Samsung Electronics          | 8         | 13.33%  |
| Micron/Crucial Technology    | 3         | 5%      |
| SK hynix                     | 2         | 3.33%   |
| Sandisk                      | 2         | 3.33%   |
| Kingston Technology Company  | 2         | 3.33%   |
| Silicon Motion               | 1         | 1.67%   |
| Shenzhen Longsys Electronics | 1         | 1.67%   |
| Phison Electronics           | 1         | 1.67%   |
| Micron Technology            | 1         | 1.67%   |
| JMicron Technology           | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 6         | 9.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 4         | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 3         | 4.69%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 3         | 4.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 3         | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 3         | 4.69%   |
| AMD 500 Series Chipset SATA Controller                                                                             | 3         | 4.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                                               | 2         | 3.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                                                         | 2         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller                                      | 2         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 2         | 3.13%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 1         | 1.56%   |
| SK hynix BC511 NVMe SSD                                                                                            | 1         | 1.56%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 1         | 1.56%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 1.56%   |
| Sandisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                                                       | 1         | 1.56%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                                                         | 1         | 1.56%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                                                        | 1         | 1.56%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                                         | 1         | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 1         | 1.56%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 1         | 1.56%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                                               | 1         | 1.56%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                                                   | 1         | 1.56%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                                               | 1         | 1.56%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                                                                   | 1         | 1.56%   |
| JMicron JMB363 SATA/IDE Controller                                                                                 | 1         | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 1         | 1.56%   |
| Intel SSD 600P Series                                                                                              | 1         | 1.56%   |
| Intel SATA Controller [RAID mode]                                                                                  | 1         | 1.56%   |
| Intel Jasper Lake SATA AHCI Controller                                                                             | 1         | 1.56%   |
| Intel Comet Lake SATA AHCI Controller                                                                              | 1         | 1.56%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                                                  | 1         | 1.56%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                                               | 1         | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 1         | 1.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 1         | 1.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                                               | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 1         | 1.56%   |
| Intel 4 Series Chipset PT IDER Controller                                                                          | 1         | 1.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                                                   | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 58.62%  |
| NVMe | 17        | 29.31%  |
| RAID | 4         | 6.9%    |
| IDE  | 3         | 5.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 30        | 69.77%  |
| AMD    | 13        | 30.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 4.65%   |
| AMD Ryzen 5 5600G with Radeon Graphics       | 2         | 4.65%   |
| AMD Ryzen 5 4600G with Radeon Graphics       | 2         | 4.65%   |
| Intel Xeon CPU X5650 @ 2.67GHz               | 1         | 2.33%   |
| Intel Pentium CPU G2020T @ 2.50GHz           | 1         | 2.33%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz             | 1         | 2.33%   |
| Intel Core i9-9900KS CPU @ 4.00GHz           | 1         | 2.33%   |
| Intel Core i9-9900 CPU @ 3.10GHz             | 1         | 2.33%   |
| Intel Core i7-8650U CPU @ 1.90GHz            | 1         | 2.33%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 2.33%   |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 2.33%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 2.33%   |
| Intel Core i7-2640M CPU @ 2.80GHz            | 1         | 2.33%   |
| Intel Core i7-2620M CPU @ 2.70GHz            | 1         | 2.33%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 1         | 2.33%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 1         | 2.33%   |
| Intel Core i5-8600 CPU @ 3.10GHz             | 1         | 2.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz            | 1         | 2.33%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 2.33%   |
| Intel Core i5-4310M CPU @ 2.70GHz            | 1         | 2.33%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 2.33%   |
| Intel Core i5-3330 CPU @ 3.00GHz             | 1         | 2.33%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 1         | 2.33%   |
| Intel Core i5 CPU                            | 1         | 2.33%   |
| Intel Core i3-7100T CPU @ 3.40GHz            | 1         | 2.33%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 1         | 2.33%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz           | 1         | 2.33%   |
| Intel Core 2 Duo                             | 1         | 2.33%   |
| Intel Celeron N5095 @ 2.00GHz                | 1         | 2.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 1         | 2.33%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz       | 1         | 2.33%   |
| AMD Ryzen 7 5825U with Radeon Graphics       | 1         | 2.33%   |
| AMD Ryzen 7 5700U with Radeon Graphics       | 1         | 2.33%   |
| AMD Ryzen 7 4700U with Radeon Graphics       | 1         | 2.33%   |
| AMD Ryzen 5 5600U with Radeon Graphics       | 1         | 2.33%   |
| AMD Ryzen 5 5600H with Radeon Graphics       | 1         | 2.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics       | 1         | 2.33%   |
| AMD PRO A6-8570E R5, 6 COMPUTE CORES 2C+4G   | 1         | 2.33%   |
| AMD PRO A10-8730B R5, 10 COMPUTE CORES 4C+6G | 1         | 2.33%   |
| AMD FX-8320 Eight-Core Processor             | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 10        | 23.26%  |
| Intel Core i7    | 8         | 18.6%   |
| AMD Ryzen 5      | 7         | 16.28%  |
| Other            | 3         | 6.98%   |
| Intel Core i3    | 3         | 6.98%   |
| AMD Ryzen 7      | 3         | 6.98%   |
| Intel Core i9    | 2         | 4.65%   |
| Intel Xeon       | 1         | 2.33%   |
| Intel Pentium    | 1         | 2.33%   |
| Intel Core m3    | 1         | 2.33%   |
| Intel Core 2 Duo | 1         | 2.33%   |
| Intel Celeron    | 1         | 2.33%   |
| AMD PRO A10      | 1         | 2.33%   |
| AMD FX           | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 41.86%  |
| 4      | 9         | 20.93%  |
| 12     | 7         | 16.28%  |
| 6      | 4         | 9.3%    |
| 8      | 3         | 6.98%   |
| 16     | 2         | 4.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 24        | 55.81%  |
| 1      | 19        | 44.19%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 10        | 23.26%  |
| Zen 3       | 5         | 11.63%  |
| Unknown     | 4         | 9.3%    |
| Zen 2       | 3         | 6.98%   |
| SandyBridge | 3         | 6.98%   |
| IvyBridge   | 3         | 6.98%   |
| Haswell     | 3         | 6.98%   |
| Skylake     | 2         | 4.65%   |
| Nehalem     | 2         | 4.65%   |
| Excavator   | 2         | 4.65%   |
| Westmere    | 1         | 2.33%   |
| TigerLake   | 1         | 2.33%   |
| Piledriver  | 1         | 2.33%   |
| Penryn      | 1         | 2.33%   |
| IceLake     | 1         | 2.33%   |
| Broadwell   | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 23        | 46%     |
| Nvidia                     | 13        | 26%     |
| AMD                        | 13        | 26%     |
| Matrox Electronics Systems | 1         | 2%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 3         | 6%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 6%      |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 3         | 6%      |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 4%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 2         | 4%      |
| AMD Lucienne                                                              | 2         | 4%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 4%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 2%      |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                  | 1         | 2%      |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                        | 1         | 2%      |
| Nvidia GT215M [GeForce GT 335M]                                           | 1         | 2%      |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 2%      |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                       | 1         | 2%      |
| Nvidia GM206 [GeForce GTX 950]                                            | 1         | 2%      |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1         | 2%      |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 2%      |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                             | 1         | 2%      |
| Nvidia GK208B [GeForce GT 710]                                            | 1         | 2%      |
| Nvidia GF119 [GeForce GT 610]                                             | 1         | 2%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 2%      |
| Matrox Electronics Systems MGA G200EH                                     | 1         | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 2%      |
| Intel Skylake-Y GT2 [HD Graphics 515]                                     | 1         | 2%      |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 1         | 2%      |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1         | 2%      |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                   | 1         | 2%      |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 1         | 2%      |
| Intel JasperLake [UHD Graphics]                                           | 1         | 2%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 2%      |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                  | 1         | 2%      |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 1         | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2%      |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 2%      |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 2%      |
| AMD Juniper XT [Radeon HD 5770]                                           | 1         | 2%      |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                         | 1         | 2%      |
| AMD Barcelo                                                               | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 41.86%  |
| 1 x AMD        | 11        | 25.58%  |
| 1 x Nvidia     | 8         | 18.6%   |
| Intel + Nvidia | 3         | 6.98%   |
| 1 x Matrox     | 1         | 2.33%   |
| Intel + AMD    | 1         | 2.33%   |
| AMD + Nvidia   | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 36        | 83.72%  |
| Proprietary | 7         | 16.28%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 65.12%  |
| 0.51-1.0   | 5         | 11.63%  |
| 0.01-0.5   | 4         | 9.3%    |
| 1.01-2.0   | 3         | 6.98%   |
| 5.01-6.0   | 2         | 4.65%   |
| 7.01-8.0   | 1         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 8         | 19.05%  |
| Samsung Electronics | 7         | 16.67%  |
| BOE                 | 7         | 16.67%  |
| Sharp               | 2         | 4.76%   |
| Goldstar            | 2         | 4.76%   |
| Dell                | 2         | 4.76%   |
| Apple               | 2         | 4.76%   |
| Sony                | 1         | 2.38%   |
| Pioneer Electronic  | 1         | 2.38%   |
| Panasonic           | 1         | 2.38%   |
| LG Display          | 1         | 2.38%   |
| ITE                 | 1         | 2.38%   |
| InfoVision          | 1         | 2.38%   |
| HKC                 | 1         | 2.38%   |
| HannStar            | 1         | 2.38%   |
| DENON               | 1         | 2.38%   |
| Chimei Innolux      | 1         | 2.38%   |
| BenQ                | 1         | 2.38%   |
| ASUSTek Computer    | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 3         | 7.14%   |
| Sharp LCD Monitor SHP1481 1920x1080 290x170mm 13.2-inch               | 2         | 4.76%   |
| Sony TV SNY4D04 1920x1080                                             | 1         | 2.38%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 600x340mm 27.2-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 2.38%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch     | 1         | 2.38%   |
| Pioneer Electronic LCD Monitor SC-1223 1920x1080                      | 1         | 2.38%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch           | 1         | 2.38%   |
| LG Display LCD Monitor LGD020C 1600x900 350x190mm 15.7-inch           | 1         | 2.38%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                 | 1         | 2.38%   |
| InfoVision LCD Monitor IVO8C69 1920x1080 310x170mm 13.9-inch          | 1         | 2.38%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                 | 1         | 2.38%   |
| HannStar LCD Monitor HSD1568 1920x1080 340x190mm 15.3-inch            | 1         | 2.38%   |
| Goldstar LG HDR 4K GSM774F 3840x2160 700x400mm 31.7-inch              | 1         | 2.38%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1         | 2.38%   |
| DENON AVR DON004B 1920x1080 1330x750mm 60.1-inch                      | 1         | 2.38%   |
| Dell P2014H DEL4097 1600x900 440x240mm 19.7-inch                      | 1         | 2.38%   |
| Dell Inspiron 549X DEL9400 1920x1080 510x290mm 23.1-inch              | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN175F 1920x1080 380x210mm 17.1-inch      | 1         | 2.38%   |
| BOE LCD Monitor BOE0A40 2560x1600 340x210mm 15.7-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE08A8 1920x1080 340x190mm 15.3-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE0731 1366x768 260x140mm 11.6-inch                  | 1         | 2.38%   |
| BOE LCD Monitor BOE06EE 1920x1080 310x170mm 13.9-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE06DF 1920x1080 310x170mm 13.9-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 1         | 2.38%   |
| BenQ GL2055 BNQ78B8 1600x900 440x250mm 19.9-inch                      | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO35EC 1366x768 340x190mm 15.3-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO206C 1366x768 280x160mm 12.7-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO142D 1920x1080 290x170mm 13.2-inch        | 1         | 2.38%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 1         | 2.38%   |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                  | 1         | 2.38%   |
| Apple Cinema HD APP9221 2560x1600 640x400mm 29.7-inch                 | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 27        | 64.29%  |
| 1366x768 (WXGA)  | 7         | 16.67%  |
| 1600x900 (HD+)   | 3         | 7.14%   |
| 3840x2160 (4K)   | 2         | 4.76%   |
| 2560x1600        | 2         | 4.76%   |
| 1440x900 (WXGA+) | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 21.43%  |
| 13      | 9         | 21.43%  |
| 23      | 4         | 9.52%   |
| 12      | 4         | 9.52%   |
| 27      | 3         | 7.14%   |
| 19      | 2         | 4.76%   |
| 17      | 2         | 4.76%   |
| 11      | 2         | 4.76%   |
| Unknown | 2         | 4.76%   |
| 60      | 1         | 2.38%   |
| 31      | 1         | 2.38%   |
| 29      | 1         | 2.38%   |
| 24      | 1         | 2.38%   |
| 21      | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 30.95%  |
| 201-300     | 11        | 26.19%  |
| 501-600     | 8         | 19.05%  |
| 401-500     | 3         | 7.14%   |
| 601-700     | 2         | 4.76%   |
| 351-400     | 2         | 4.76%   |
| Unknown     | 2         | 4.76%   |
| 1001-1500   | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 38        | 90.48%  |
| 16/10   | 3         | 7.14%   |
| Unknown | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 7         | 16.67%  |
| 201-250        | 6         | 14.29%  |
| 81-90          | 5         | 11.9%   |
| 71-80          | 4         | 9.52%   |
| 61-70          | 4         | 9.52%   |
| 301-350        | 3         | 7.14%   |
| 51-60          | 2         | 4.76%   |
| 351-500        | 2         | 4.76%   |
| 151-200        | 2         | 4.76%   |
| 121-130        | 2         | 4.76%   |
| Unknown        | 2         | 4.76%   |
| More than 1000 | 1         | 2.38%   |
| 111-120        | 1         | 2.38%   |
| 101-110        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 40.48%  |
| 51-100        | 10        | 23.81%  |
| 161-240       | 6         | 14.29%  |
| 101-120       | 5         | 11.9%   |
| Unknown       | 2         | 4.76%   |
| More than 240 | 1         | 2.38%   |
| 1-50          | 1         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 93.02%  |
| 0     | 3         | 6.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 29        | 45.31%  |
| Realtek Semiconductor             | 19        | 29.69%  |
| Qualcomm Atheros                  | 6         | 9.38%   |
| Broadcom                          | 5         | 7.81%   |
| TP-Link                           | 2         | 3.13%   |
| Ralink Technology                 | 1         | 1.56%   |
| Huawei Technologies               | 1         | 1.56%   |
| Ericsson Business Mobile Networks | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller      | 15        | 19.23%  |
| Intel Wireless 7265                                                         | 6         | 7.69%   |
| Intel Wi-Fi 6 AX200                                                         | 4         | 5.13%   |
| Intel Wireless 8265 / 8275                                                  | 3         | 3.85%   |
| Intel Wireless 7260                                                         | 3         | 3.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 2         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 2.56%   |
| Intel Wireless 3160                                                         | 2         | 2.56%   |
| Intel Ethernet Connection I218-LM                                           | 2         | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                                       | 2         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 2         | 2.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1         | 1.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 1         | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.28%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                 | 1         | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 1.28%   |
| Realtek Killer E3000 2.5GbE Controller                                      | 1         | 1.28%   |
| Ralink RT5372 Wireless Adapter                                              | 1         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 1         | 1.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                   | 1         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                       | 1         | 1.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 1         | 1.28%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                   | 1         | 1.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                             | 1         | 1.28%   |
| Intel Ethernet Controller I225-V                                            | 1         | 1.28%   |
| Intel Ethernet Connection I217-LM                                           | 1         | 1.28%   |
| Intel Ethernet Connection (7) I219-V                                        | 1         | 1.28%   |
| Intel Ethernet Connection (6) I219-LM                                       | 1         | 1.28%   |
| Intel Ethernet Connection (5) I219-LM                                       | 1         | 1.28%   |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 1.28%   |
| Intel Ethernet Connection (14) I219-V                                       | 1         | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 1         | 1.28%   |
| Intel 82574L Gigabit Network Connection                                     | 1         | 1.28%   |
| Intel 82567LM-3 Gigabit Network Connection                                  | 1         | 1.28%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                            | 1         | 1.28%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 57.5%   |
| Realtek Semiconductor | 6         | 15%     |
| Qualcomm Atheros      | 4         | 10%     |
| Broadcom              | 4         | 10%     |
| TP-Link               | 2         | 5%      |
| Ralink Technology     | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 6         | 15%     |
| Intel Wi-Fi 6 AX200                                            | 4         | 10%     |
| Intel Wireless 8265 / 8275                                     | 3         | 7.5%    |
| Intel Wireless 7260                                            | 3         | 7.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 5%      |
| Intel Wireless 3160                                            | 2         | 5%      |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 2.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.5%    |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 2.5%    |
| Ralink RT5372 Wireless Adapter                                 | 1         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 2.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.5%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 2.5%    |
| Broadcom BCM43143 802.11bgn (1x1) Wireless Adapter             | 1         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.5%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 45.71%  |
| Intel                 | 15        | 42.86%  |
| Qualcomm Atheros      | 3         | 8.57%   |
| Broadcom              | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15        | 42.86%  |
| Intel Ethernet Connection I218-LM                                      | 2         | 5.71%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 5.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 2.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 2.86%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 2.86%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 2.86%   |
| Intel Ethernet Controller I225-V                                       | 1         | 2.86%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.86%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 2.86%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 2.86%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 2.86%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.86%   |
| Intel Ethernet Connection (14) I219-V                                  | 1         | 2.86%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 2.86%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 2.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 49.33%  |
| Ethernet | 35        | 46.67%  |
| Unknown  | 2         | 2.67%   |
| Modem    | 1         | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 23        | 57.5%   |
| WiFi     | 17        | 42.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 26        | 60.47%  |
| 1     | 17        | 39.53%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 97.67%  |
| Yes  | 1         | 2.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 66.67%  |
| Realtek Semiconductor           | 4         | 13.33%  |
| Qualcomm Atheros Communications | 2         | 6.67%   |
| Skylight Digital                | 1         | 3.33%   |
| Qcom                            | 1         | 3.33%   |
| Lite-On Technology              | 1         | 3.33%   |
| Apple                           | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 12        | 40%     |
| Intel AX200 Bluetooth                          | 4         | 13.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 10%     |
| Realtek Bluetooth Adapter                      | 2         | 6.67%   |
| Skylight Digital Realtek Bluetooth Adapter     | 1         | 3.33%   |
| Realtek Wireless Bluetooth Adapter             | 1         | 3.33%   |
| Realtek Bluetooth 4.2 Adapter                  | 1         | 3.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1         | 1         | 3.33%   |
| Qualcomm Atheros AR3011 Bluetooth              | 1         | 3.33%   |
| Qcom Broadcom Bluetooth USB                    | 1         | 3.33%   |
| Lite-On Atheros Bluetooth                      | 1         | 3.33%   |
| Intel AX210 Bluetooth                          | 1         | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 30        | 49.18%  |
| AMD                 | 15        | 24.59%  |
| Nvidia              | 11        | 18.03%  |
| C-Media Electronics | 2         | 3.28%   |
| Tenx Technology     | 1         | 1.64%   |
| Microsoft           | 1         | 1.64%   |
| GN Netcom           | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 10        | 13.16%  |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 8         | 10.53%  |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 7.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 5.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.63%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.63%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.63%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.63%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 2.63%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.63%   |
| Tenx Technology USB  AUDIO                                                 | 1         | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.32%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.32%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 1.32%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.32%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.32%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1.32%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.32%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.32%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.32%   |
| Microsoft LifeChat LX-3000 Headset                                         | 1         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.32%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.32%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.32%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.32%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.32%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.32%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                            | 1         | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 23.08%  |
| SK hynix            | 9         | 17.31%  |
| Micron Technology   | 8         | 15.38%  |
| Kingston            | 7         | 13.46%  |
| Crucial             | 4         | 7.69%   |
| Ramaxel Technology  | 3         | 5.77%   |
| Unknown             | 3         | 5.77%   |
| Corsair             | 2         | 3.85%   |
| Unknown             | 1         | 1.92%   |
| Team                | 1         | 1.92%   |
| Hewlett-Packard     | 1         | 1.92%   |
| G.Skill             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 3         | 5.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 3.7%    |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 2         | 3.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 3.7%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 3.7%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                        | 1         | 1.85%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2667MT/s               | 1         | 1.85%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 667MT/s                 | 1         | 1.85%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.85%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.85%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.85%   |
| Samsung RAM M471B1G73QHO-YKO 4GB SODIMM DDR3 1600MT/s            | 1         | 1.85%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.85%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.85%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.85%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB DIMM DDR4 3200MT/s              | 1         | 1.85%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.85%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s              | 1         | 1.85%   |
| Samsung RAM D24D4S7S8MA-8 8GB Row Of Chips LPDDR4 3733MT/s       | 1         | 1.85%   |
| Ramaxel RAM RMSA3310MF96HAF-3200 8GB SODIMM DDR4 3200MT/s        | 1         | 1.85%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.85%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.85%   |
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s | 1         | 1.85%   |
| Micron RAM MT52L256M32D1PF-10 2GB LPDDR3 1867MT/s                | 1         | 1.85%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.85%   |
| Micron RAM 8KTF51264HZ-1G4E1 4GB SODIMM DDR3 1333MT/s            | 1         | 1.85%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.85%   |
| Micron RAM 16JTF51264AZ 4GB DIMM DDR3 667MT/s                    | 1         | 1.85%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 1.85%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                        | 1         | 1.85%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s          | 1         | 1.85%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1         | 1.85%   |
| Kingston RAM 99U5584-007.A 4GB DIMM DDR3 667MT/s                 | 1         | 1.85%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s            | 1         | 1.85%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s            | 1         | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 50%     |
| DDR3    | 14        | 31.82%  |
| LPDDR4  | 3         | 6.82%   |
| LPDDR3  | 3         | 6.82%   |
| DDR2    | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 54.55%  |
| DIMM         | 14        | 31.82%  |
| Row Of Chips | 5         | 11.36%  |
| Unknown      | 1         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 42.55%  |
| 4096  | 14        | 29.79%  |
| 16384 | 5         | 10.64%  |
| 32768 | 4         | 8.51%   |
| 2048  | 4         | 8.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 11        | 23.91%  |
| 1600  | 9         | 19.57%  |
| 2667  | 5         | 10.87%  |
| 2400  | 4         | 8.7%    |
| 1333  | 4         | 8.7%    |
| 1867  | 3         | 6.52%   |
| 2133  | 2         | 4.35%   |
| 1334  | 2         | 4.35%   |
| 4267  | 1         | 2.17%   |
| 3733  | 1         | 2.17%   |
| 3600  | 1         | 2.17%   |
| 1066  | 1         | 2.17%   |
| 800   | 1         | 2.17%   |
| 667   | 1         | 2.17%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Microdia                      | 7         | 29.17%  |
| Chicony Electronics           | 5         | 20.83%  |
| Lite-On Technology            | 3         | 12.5%   |
| Realtek Semiconductor         | 2         | 8.33%   |
| IMC Networks                  | 2         | 8.33%   |
| USB Camera                    | 1         | 4.17%   |
| Sunplus Innovation Technology | 1         | 4.17%   |
| Quanta                        | 1         | 4.17%   |
| Intel                         | 1         | 4.17%   |
| Bison Electronics             | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Laptop_Integrated_Webcam_HD     | 2         | 8.33%   |
| Microdia Integrated Webcam HD            | 2         | 8.33%   |
| USB Camera USB Camera                    | 1         | 4.17%   |
| Sunplus Integrated_Webcam_HD             | 1         | 4.17%   |
| Realtek PC Camera                        | 1         | 4.17%   |
| Realtek Integrated Webcam HD             | 1         | 4.17%   |
| Quanta LG Webcam                         | 1         | 4.17%   |
| Microdia USB Camera                      | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD            | 1         | 4.17%   |
| Microdia Integrated Webcam               | 1         | 4.17%   |
| Lite-On Realtek PC Camera                | 1         | 4.17%   |
| Lite-On Integrated Camera                | 1         | 4.17%   |
| Lite-On HP HD Camera                     | 1         | 4.17%   |
| Intel RealSense 3D Camera (Front F200)   | 1         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 4.17%   |
| IMC Networks USB 2.0 UVC HD Webcam       | 1         | 4.17%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 4.17%   |
| Chicony Integrated HP HD Webcam          | 1         | 4.17%   |
| Chicony Integrated Camera                | 1         | 4.17%   |
| Chicony HP Wide Vision HD Camera         | 1         | 4.17%   |
| Chicony HP HD Camera                     | 1         | 4.17%   |
| Bison SunplusIT INC. Integrated Camera   | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 45.45%  |
| Elan Microelectronics      | 2         | 18.18%  |
| Synaptics                  | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| FocalTech Systems          | 1         | 9.09%   |
| Fingerprint Cards          | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 2         | 18.18%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 18.18%  |
| Elan Fingerprint Sensor                           | 2         | 18.18%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 9.09%   |
| FocalTech Systems Fingerprint Reader              | 1         | 9.09%   |
| Fingerprint Cards FPC Fingerprint Reader          | 1         | 9.09%   |

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
| 2     | 17        | 39.53%  |
| 1     | 11        | 25.58%  |
| 3     | 7         | 16.28%  |
| 0     | 6         | 13.95%  |
| 5     | 2         | 4.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 27        | 38.57%  |
| Bluetooth                | 18        | 25.71%  |
| Fingerprint reader       | 10        | 14.29%  |
| Net/wireless             | 8         | 11.43%  |
| Network                  | 2         | 2.86%   |
| Firewire controller      | 2         | 2.86%   |
| Card reader              | 2         | 2.86%   |
| Sound                    | 1         | 1.43%   |

