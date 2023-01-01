helloSystem 0.8.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 62

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Dell          | Latitude 5590               | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Acer          | Aspire 5251                 | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| Dell          | Inspiron 3421               | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Google        | Edgar                       | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Apple         | MacBook5,2                  | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Dell          | Latitude E5550              | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Toshiba       | Satellite S55t-B            | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| HP            | OMEN by Laptop              | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| Dell          | Latitude E5450              | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| Acer          | Aspire E5-571G              | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| HP            | 250 G6 Notebook PC          | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| HP            | Unknown                     | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Timi          | TM1701                      | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| TUXEDO        | Aura 15 Gen1                | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Inspiron 5559               | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | [4b5603b38b](https://bsd-hardware.info/?probe=4b5603b38b) | Apr 29, 2022 |
| ASUSTek       | 1001PX                      | [b47a498f2e](https://bsd-hardware.info/?probe=b47a498f2e) | Apr 08, 2022 |
| Dell          | Latitude E5470              | [a7d087a428](https://bsd-hardware.info/?probe=a7d087a428) | Apr 05, 2022 |
| Sony          | VGN-AW21S_B                 | [11edcb4e82](https://bsd-hardware.info/?probe=11edcb4e82) | Apr 03, 2022 |
| PCSTICK       | Unknown                     | [6f9f24b262](https://bsd-hardware.info/?probe=6f9f24b262) | Mar 29, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [93655cdd83](https://bsd-hardware.info/?probe=93655cdd83) | Mar 21, 2022 |
| HP            | EliteBook 850 G3            | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| Gateway       | NE56R                       | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| HUAWEI        | BOD-WXX9                    | [65454bcc92](https://bsd-hardware.info/?probe=65454bcc92) | Mar 06, 2022 |
| Acer          | V5-131                      | [076ca78b3f](https://bsd-hardware.info/?probe=076ca78b3f) | Feb 25, 2022 |
| Dell          | Latitude 7480               | [8a0388b49d](https://bsd-hardware.info/?probe=8a0388b49d) | Feb 23, 2022 |
| PCSTICK       | Unknown                     | [b76b5c9670](https://bsd-hardware.info/?probe=b76b5c9670) | Feb 21, 2022 |
| ASUSTek       | 1001PX                      | [d171d1ec99](https://bsd-hardware.info/?probe=d171d1ec99) | Feb 17, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Acer          | Aspire 5750G                | [bd22fc8a49](https://bsd-hardware.info/?probe=bd22fc8a49) | Feb 15, 2022 |
| Timi          | RedmiBook Pro 15            | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Apple         | MacBook5,2                  | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| Sony          | VPCEB1J1E                   | [9151a22f13](https://bsd-hardware.info/?probe=9151a22f13) | Jan 30, 2022 |
| Lenovo        | ThinkPad T440 20B7A0B7MS    | [be30041f4e](https://bsd-hardware.info/?probe=be30041f4e) | Jan 10, 2022 |
| Lenovo        | G480 20149                  | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| HP            | EliteBook 820 G1            | [362940acbb](https://bsd-hardware.info/?probe=362940acbb) | Jan 03, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 53        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 49        | 92.45%  |
| GNOME        | 2         | 3.77%   |
| Window Maker | 1         | 1.89%   |
| Cinnamon     | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 53        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 52        | 98.11%  |
| GDM  | 1         | 1.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 49        | 92.45%  |
| ru_RU | 1         | 1.89%   |
| es_ES | 1         | 1.89%   |
| en    | 1         | 1.89%   |
| de    | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 53        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 37        | 69.81%  |
| Zfs    | 16        | 30.19%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 53        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 10        | 18.87%  |
| Lenovo           | 9         | 16.98%  |
| Hewlett-Packard  | 7         | 13.21%  |
| ASUSTek Computer | 4         | 7.55%   |
| Apple            | 4         | 7.55%   |
| Acer             | 4         | 7.55%   |
| TUXEDO           | 2         | 3.77%   |
| Toshiba          | 2         | 3.77%   |
| Timi             | 2         | 3.77%   |
| Sony             | 2         | 3.77%   |
| PCSTICK          | 1         | 1.89%   |
| Packard Bell     | 1         | 1.89%   |
| MSI              | 1         | 1.89%   |
| Kraftway         | 1         | 1.89%   |
| HUAWEI           | 1         | 1.89%   |
| Google           | 1         | 1.89%   |
| Gateway          | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| HP 250 G6 Notebook PC                        | 2         | 3.77%   |
| Apple MacBook5,2                             | 2         | 3.77%   |
| Unknown                                      | 2         | 3.77%   |
| TUXEDO Pulse 14 Gen1                         | 1         | 1.89%   |
| TUXEDO Aura 15 Gen1                          | 1         | 1.89%   |
| Toshiba TECRA Z40-C-12Z                      | 1         | 1.89%   |
| Toshiba Satellite S55t-B                     | 1         | 1.89%   |
| Timi TM1701                                  | 1         | 1.89%   |
| Timi RedmiBook Pro 15                        | 1         | 1.89%   |
| Sony VPCEB1J1E                               | 1         | 1.89%   |
| Sony VGN-AW21S_B                             | 1         | 1.89%   |
| Packard Bell EasyNote_MX52-B-071             | 1         | 1.89%   |
| MSI PS63 Modern 8M                           | 1         | 1.89%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00        | 1         | 1.89%   |
| Lenovo ThinkPad X250 20CLS23500              | 1         | 1.89%   |
| Lenovo ThinkPad X250 20CLS1WP01              | 1         | 1.89%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 1.89%   |
| Lenovo ThinkPad T440 20B7A0B7MS              | 1         | 1.89%   |
| Lenovo ThinkPad T420 4178A72                 | 1         | 1.89%   |
| Lenovo Legion 5 15ARH05 82B5                 | 1         | 1.89%   |
| Lenovo IdeaPad 3 15IGL05 82BU                | 1         | 1.89%   |
| Lenovo G480 20149                            | 1         | 1.89%   |
| Kraftway KW10T                               | 1         | 1.89%   |
| HUAWEI BOD-WXX9                              | 1         | 1.89%   |
| HP Pavilion g6                               | 1         | 1.89%   |
| HP OMEN by Laptop                            | 1         | 1.89%   |
| HP EliteBook 850 G3                          | 1         | 1.89%   |
| HP EliteBook 820 G1                          | 1         | 1.89%   |
| Google Edgar                                 | 1         | 1.89%   |
| Gateway NE56R                                | 1         | 1.89%   |
| Dell Studio 1747                             | 1         | 1.89%   |
| Dell Latitude E6540                          | 1         | 1.89%   |
| Dell Latitude E5550                          | 1         | 1.89%   |
| Dell Latitude E5470                          | 1         | 1.89%   |
| Dell Latitude E5450                          | 1         | 1.89%   |
| Dell Latitude 7480                           | 1         | 1.89%   |
| Dell Latitude 5590                           | 1         | 1.89%   |
| Dell Inspiron 5559                           | 1         | 1.89%   |
| Dell Inspiron 3421                           | 1         | 1.89%   |
| Dell Inspiron 15-3552                        | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 11.32%  |
| Dell Latitude         | 6         | 11.32%  |
| Acer Aspire           | 4         | 7.55%   |
| Dell Inspiron         | 3         | 5.66%   |
| HP EliteBook          | 2         | 3.77%   |
| HP 250                | 2         | 3.77%   |
| Apple MacBook5        | 2         | 3.77%   |
| Unknown               | 2         | 3.77%   |
| TUXEDO Pulse          | 1         | 1.89%   |
| TUXEDO Aura           | 1         | 1.89%   |
| Toshiba TECRA         | 1         | 1.89%   |
| Toshiba Satellite     | 1         | 1.89%   |
| Timi TM1701           | 1         | 1.89%   |
| Timi RedmiBook        | 1         | 1.89%   |
| Sony VPCEB1J1E        | 1         | 1.89%   |
| Sony VGN-AW21S        | 1         | 1.89%   |
| Packard Bell EasyNote | 1         | 1.89%   |
| MSI PS63              | 1         | 1.89%   |
| Lenovo Legion         | 1         | 1.89%   |
| Lenovo IdeaPad        | 1         | 1.89%   |
| Lenovo G480           | 1         | 1.89%   |
| Kraftway KW10T        | 1         | 1.89%   |
| HUAWEI BOD-WXX9       | 1         | 1.89%   |
| HP Pavilion           | 1         | 1.89%   |
| HP OMEN               | 1         | 1.89%   |
| Google Edgar          | 1         | 1.89%   |
| Gateway NE56R         | 1         | 1.89%   |
| Dell Studio           | 1         | 1.89%   |
| ASUS VivoBook         | 1         | 1.89%   |
| ASUS UX31E            | 1         | 1.89%   |
| ASUS F6A              | 1         | 1.89%   |
| ASUS 1001PX           | 1         | 1.89%   |
| Apple MacBookAir5     | 1         | 1.89%   |
| Apple MacBook6        | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 7         | 13.21%  |
| 2019 | 6         | 11.32%  |
| 2022 | 4         | 7.55%   |
| 2016 | 4         | 7.55%   |
| 2015 | 4         | 7.55%   |
| 2012 | 4         | 7.55%   |
| 2009 | 4         | 7.55%   |
| 2021 | 3         | 5.66%   |
| 2018 | 3         | 5.66%   |
| 2014 | 3         | 5.66%   |
| 2010 | 3         | 5.66%   |
| 2017 | 2         | 3.77%   |
| 2013 | 2         | 3.77%   |
| 2011 | 2         | 3.77%   |
| 2008 | 1         | 1.89%   |
| 2007 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 53        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 98.11%  |
| Yes  | 1         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 20        | 37.74%  |
| 4.01-8.0   | 17        | 32.08%  |
| 16.01-24.0 | 9         | 16.98%  |
| 32.01-64.0 | 3         | 5.66%   |
| 2.01-3.0   | 3         | 5.66%   |
| 3.01-4.0   | 1         | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 37        | 69.81%  |
| 0.51-1.0 | 11        | 20.75%  |
| 1.01-2.0 | 5         | 9.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 67.92%  |
| 2      | 11        | 20.75%  |
| 0      | 5         | 9.43%   |
| 3      | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 67.92%  |
| Yes       | 17        | 32.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 77.36%  |
| No        | 12        | 22.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 96.23%  |
| No        | 2         | 3.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 67.92%  |
| No        | 17        | 32.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Germany   | 6         | 11.32%  |
| USA       | 5         | 9.43%   |
| Russia    | 5         | 9.43%   |
| Brazil    | 4         | 7.55%   |
| Ukraine   | 3         | 5.66%   |
| China     | 3         | 5.66%   |
| UK        | 2         | 3.77%   |
| Spain     | 2         | 3.77%   |
| Mexico    | 2         | 3.77%   |
| Italy     | 2         | 3.77%   |
| Hungary   | 2         | 3.77%   |
| Canada    | 2         | 3.77%   |
| Venezuela | 1         | 1.89%   |
| UAE       | 1         | 1.89%   |
| Taiwan    | 1         | 1.89%   |
| Sweden    | 1         | 1.89%   |
| Slovenia  | 1         | 1.89%   |
| Slovakia  | 1         | 1.89%   |
| Romania   | 1         | 1.89%   |
| Peru      | 1         | 1.89%   |
| Panama    | 1         | 1.89%   |
| Norway    | 1         | 1.89%   |
| Georgia   | 1         | 1.89%   |
| France    | 1         | 1.89%   |
| Belarus   | 1         | 1.89%   |
| Argentina | 1         | 1.89%   |
| Albania   | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Yunlin               | 1         | 1.89%   |
| Weifang              | 1         | 1.89%   |
| Warendorf            | 1         | 1.89%   |
| Vladivostok          | 1         | 1.89%   |
| Vancouver            | 1         | 1.89%   |
| Ufa                  | 1         | 1.89%   |
| Szeged               | 1         | 1.89%   |
| Sao Paulo            | 1         | 1.89%   |
| San Carlos del Zulia | 1         | 1.89%   |
| Rio das Ostras       | 1         | 1.89%   |
| Rho                  | 1         | 1.89%   |
| Redondela            | 1         | 1.89%   |
| Perm                 | 1         | 1.89%   |
| Panama City          | 1         | 1.89%   |
| Ottawa               | 1         | 1.89%   |
| Orizaba              | 1         | 1.89%   |
| Odessa               | 1         | 1.89%   |
| Oakdale              | 1         | 1.89%   |
| Nesttun              | 1         | 1.89%   |
| Nanticoke            | 1         | 1.89%   |
| Munich               | 1         | 1.89%   |
| Moscow               | 1         | 1.89%   |
| Mirepeix             | 1         | 1.89%   |
| Minsk                | 1         | 1.89%   |
| Mexico City          | 1         | 1.89%   |
| Mendoza              | 1         | 1.89%   |
| Maracanau            | 1         | 1.89%   |
| LogroÃ±o           | 1         | 1.89%   |
| Linyi                | 1         | 1.89%   |
| Lima                 | 1         | 1.89%   |
| Lanzhou              | 1         | 1.89%   |
| Kyiv                 | 1         | 1.89%   |
| Kresnice             | 1         | 1.89%   |
| Kazincbarcika        | 1         | 1.89%   |
| K'alak'i T'bilisi    | 1         | 1.89%   |
| Ipojuca              | 1         | 1.89%   |
| Hampton              | 1         | 1.89%   |
| Feltham              | 1         | 1.89%   |
| Farka e Madhe        | 1         | 1.89%   |
| Dumfries             | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 15%     |
| Samsung Electronics | 9         | 11     | 15%     |
| WDC                 | 7         | 7      | 11.67%  |
| Kingston            | 6         | 6      | 10%     |
| Toshiba             | 5         | 5      | 8.33%   |
| Intel               | 4         | 4      | 6.67%   |
| Hitachi             | 3         | 3      | 5%      |
| SK hynix            | 2         | 2      | 3.33%   |
| Fujitsu             | 2         | 2      | 3.33%   |
| A-DATA Technology   | 2         | 2      | 3.33%   |
| Transcend           | 1         | 1      | 1.67%   |
| SSSTC               | 1         | 1      | 1.67%   |
| SanDisk             | 1         | 1      | 1.67%   |
| PNY                 | 1         | 1      | 1.67%   |
| Patriot             | 1         | 1      | 1.67%   |
| OCZ                 | 1         | 1      | 1.67%   |
| KIOXIA              | 1         | 1      | 1.67%   |
| KingSpec            | 1         | 1      | 1.67%   |
| GOODRAM             | 1         | 1      | 1.67%   |
| FORESEE             | 1         | 1      | 1.67%   |
| Apple               | 1         | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                  | 2         | 3.23%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 3.23%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 1.61%   |
| WDC WDS100T2B0A-00SM50 1TB                | 1         | 1.61%   |
| WDC WDBNCE5000PNC 500GB                   | 1         | 1.61%   |
| WDC WD5000LPCX-60VHAT0 500GB              | 1         | 1.61%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1.61%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 1.61%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 1.61%   |
| Transcend TS120GMTS420S 120GB             | 1         | 1.61%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.61%   |
| Toshiba MK8034GSX 80GB                    | 1         | 1.61%   |
| Toshiba KSG60ZMV256G 256GB                | 1         | 1.61%   |
| SSSTC CL1-4D128 128GB                     | 1         | 1.61%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 1.61%   |
| SK hynix BC711 NVMe 512GB                 | 1         | 1.61%   |
| Seagate ST9500420AS 500GB                 | 1         | 1.61%   |
| Seagate ST9160821AS 160GB                 | 1         | 1.61%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 1.61%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1.61%   |
| Seagate ST320LT014-9YK142 320GB           | 1         | 1.61%   |
| SanDisk SSD PLUS 120GB                    | 1         | 1.61%   |
| Samsung SSD 980 1TB                       | 1         | 1.61%   |
| Samsung SSD 970 EVO Plus 250GB            | 1         | 1.61%   |
| Samsung SSD 970 EVO 250GB                 | 1         | 1.61%   |
| Samsung SSD 870 EVO 2TB                   | 1         | 1.61%   |
| Samsung SSD 860 PRO 512GB                 | 1         | 1.61%   |
| Samsung SSD 860 EVO 500GB                 | 1         | 1.61%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 1.61%   |
| Samsung SSD 850 EVO 120GB                 | 1         | 1.61%   |
| Samsung MZVLW256HEHP-000L7 256GB          | 1         | 1.61%   |
| Samsung MZNTY128HDHP-00000 128GB          | 1         | 1.61%   |
| Samsung MZMPA128HMFU-000H1 128GB          | 1         | 1.61%   |
| PNY CS900 240GB SSD                       | 1         | 1.61%   |
| Patriot Burst 120GB                       | 1         | 1.61%   |
| OCZ AGILITY3 120GB                        | 1         | 1.61%   |
| KIOXIA KBG40ZNV512G 512GB                 | 1         | 1.61%   |
| Kingston SV300S37A120G 120GB              | 1         | 1.61%   |
| Kingston SNVS2000G 2TB                    | 1         | 1.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 9      | 45%     |
| Toshiba | 4         | 4      | 20%     |
| WDC     | 3         | 3      | 15%     |
| Hitachi | 3         | 3      | 15%     |
| Fujitsu | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 22.58%  |
| Kingston            | 5         | 5      | 16.13%  |
| Intel               | 4         | 4      | 12.9%   |
| WDC                 | 3         | 3      | 9.68%   |
| Transcend           | 1         | 1      | 3.23%   |
| Toshiba             | 1         | 1      | 3.23%   |
| SanDisk             | 1         | 1      | 3.23%   |
| PNY                 | 1         | 1      | 3.23%   |
| Patriot             | 1         | 1      | 3.23%   |
| OCZ                 | 1         | 1      | 3.23%   |
| KingSpec            | 1         | 1      | 3.23%   |
| GOODRAM             | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |
| FORESEE             | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 27        | 31     | 50%     |
| HDD  | 16        | 20     | 29.63%  |
| NVMe | 11        | 11     | 20.37%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 51     | 78.85%  |
| NVMe | 11        | 11     | 21.15%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 41     | 78.57%  |
| 0.51-1.0   | 8         | 9      | 19.05%  |
| 1.01-2.0   | 1         | 1      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 33        | 62.26%  |
| 101-250    | 9         | 16.98%  |
| 251-500    | 5         | 9.43%   |
| 501-1000   | 4         | 7.55%   |
| 21-50      | 1         | 1.89%   |
| Unknown    | 1         | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 50        | 94.34%  |
| 101-250 | 1         | 1.89%   |
| 51-100  | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 7.69%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 7.69%   |
| Toshiba MK8034GSX 80GB                       | 1         | 1      | 7.69%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 7.69%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 7.69%   |
| Seagate ST320LT014-9YK142 320GB              | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 7.69%   |
| Samsung Electronics MZMPA128HMFU-000H1 128GB | 1         | 1      | 7.69%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 7.69%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 7.69%   |
| Hitachi HTS541612J9SA00 120GB                | 1         | 1      | 7.69%   |
| Fujitsu MHZ2160BH FFS G1 160GB               | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 30.77%  |
| Toshiba             | 3         | 3      | 23.08%  |
| Hitachi             | 3         | 3      | 23.08%  |
| WDC                 | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Fujitsu             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 33.33%  |
| Toshiba | 3         | 3      | 25%     |
| Hitachi | 3         | 3      | 25%     |
| WDC     | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

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
| Works   | 40        | 49     | 80%     |
| Malfunc | 10        | 13     | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 37        | 64.91%  |
| AMD                            | 5         | 8.77%   |
| Samsung Electronics            | 4         | 7.02%   |
| Nvidia                         | 3         | 5.26%   |
| SK hynix                       | 2         | 3.51%   |
| Solid State Storage Technology | 1         | 1.75%   |
| SanDisk                        | 1         | 1.75%   |
| Realtek Semiconductor          | 1         | 1.75%   |
| KIOXIA                         | 1         | 1.75%   |
| Kingston Technology Company    | 1         | 1.75%   |
| JMicron Technology             | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 11.86%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 8.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 6.78%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 5.08%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 5.08%   |
| Unknown                                                                          | 3         | 5.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 3.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 3.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 3.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 3.39%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 1.69%   |
| SK hynix BC511                                                                   | 1         | 1.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.69%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.69%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.69%   |
| JMicron JMB368 IDE controller                                                    | 1         | 1.69%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.69%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.69%   |
| AMD SB600 IDE                                                                    | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 41        | 70.69%  |
| NVMe | 11        | 18.97%  |
| RAID | 3         | 5.17%   |
| IDE  | 3         | 5.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 88.68%  |
| AMD    | 6         | 11.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-6600U CPU @ 2.60GHz        | 2         | 3.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 3.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 2         | 3.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 3.77%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz     | 2         | 3.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 2         | 3.77%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.89%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 1.89%   |
| Intel Pentium CPU 4417U @ 2.30GHz        | 1         | 1.89%   |
| Intel CPU Version                        | 1         | 1.89%   |
| Intel Core i7-8650U CPU @ 1.90GHz        | 1         | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 1         | 1.89%   |
| Intel Core i7-5500U CPU @ 2.40GHz        | 1         | 1.89%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 1         | 1.89%   |
| Intel Core i7-2677M CPU @ 1.80GHz        | 1         | 1.89%   |
| Intel Core i7-2620M CPU @ 2.70GHz        | 1         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 1.89%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz       | 1         | 1.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 1         | 1.89%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 1         | 1.89%   |
| Intel Core i5-4310U CPU @ 2.00GHz        | 1         | 1.89%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 1         | 1.89%   |
| Intel Core i5-3317U CPU @ 1.70GHz        | 1         | 1.89%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 1         | 1.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.89%   |
| Intel Core i3-7020U CPU @ 2.30GHz        | 1         | 1.89%   |
| Intel Core i3-5010U CPU @ 2.10GHz        | 1         | 1.89%   |
| Intel Core i3-3217U CPU @ 1.80GHz        | 1         | 1.89%   |
| Intel Core i3-2350M CPU @ 2.30GHz        | 1         | 1.89%   |
| Intel Core i3 CPU M 330 @ 2.13GHz        | 1         | 1.89%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 1         | 1.89%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz     | 1         | 1.89%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz     | 1         | 1.89%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 1         | 1.89%   |
| Intel Celeron CPU N3160 @ 1.60GHz        | 1         | 1.89%   |
| Intel Celeron CPU B830 @ 1.80GHz         | 1         | 1.89%   |
| Intel Atom CPU Z3735F @ 1.33GHz          | 1         | 1.89%   |
| Intel Atom CPU N450 @ 1.66GHz            | 1         | 1.89%   |
| Intel Atom CPU E3825 @ 1.33GHz           | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 15        | 28.3%   |
| Intel Core i7        | 9         | 16.98%  |
| Intel Core i3        | 5         | 9.43%   |
| Intel Core 2 Duo     | 5         | 9.43%   |
| Other                | 4         | 7.55%   |
| Intel Celeron        | 3         | 5.66%   |
| Intel Atom           | 3         | 5.66%   |
| AMD Ryzen 7          | 3         | 5.66%   |
| Intel Pentium        | 2         | 3.77%   |
| Intel Pentium Silver | 1         | 1.89%   |
| AMD V120             | 1         | 1.89%   |
| AMD Athlon 64 X2     | 1         | 1.89%   |
| AMD A8               | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 29        | 54.72%  |
| 4       | 14        | 26.42%  |
| Unknown | 4         | 7.55%   |
| 16      | 2         | 3.77%   |
| 8       | 2         | 3.77%   |
| 1       | 2         | 3.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 94.34%  |
| 2      | 3         | 5.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 33        | 62.26%  |
| 1       | 16        | 30.19%  |
| Unknown | 4         | 7.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Skylake       | 7         | 13.21%  |
| SandyBridge   | 6         | 11.32%  |
| KabyLake      | 6         | 11.32%  |
| Broadwell     | 6         | 11.32%  |
| Penryn        | 5         | 9.43%   |
| Silvermont    | 4         | 7.55%   |
| Zen 2         | 3         | 5.66%   |
| Haswell       | 3         | 5.66%   |
| TigerLake     | 2         | 3.77%   |
| IvyBridge     | 2         | 3.77%   |
| Goldmont plus | 2         | 3.77%   |
| Westmere      | 1         | 1.89%   |
| Piledriver    | 1         | 1.89%   |
| Nehalem       | 1         | 1.89%   |
| K8 Hammer     | 1         | 1.89%   |
| K10           | 1         | 1.89%   |
| Bonnell       | 1         | 1.89%   |
| Unknown       | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 63.64%  |
| Nvidia | 14        | 21.21%  |
| AMD    | 10        | 15.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                                   | 6         | 9.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 9.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 7.58%   |
| AMD Renoir                                                                               | 3         | 4.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.03%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 3.03%   |
| Intel UHD Graphics 620                                                                   | 2         | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.03%   |
| Intel HD Graphics 620                                                                    | 2         | 3.03%   |
| Intel HD Graphics 530                                                                    | 2         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.03%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.52%   |
| Nvidia TU117M                                                                            | 1         | 1.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.52%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.52%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.52%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 1.52%   |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 1.52%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.52%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.52%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.52%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.52%   |
| Intel HD Graphics 610                                                                    | 1         | 1.52%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.52%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.52%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 1.52%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.52%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 1.52%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.52%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 1.52%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 1.52%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 52.83%  |
| Intel + Nvidia | 9         | 16.98%  |
| 1 x AMD        | 6         | 11.32%  |
| 1 x Nvidia     | 4         | 7.55%   |
| Intel + AMD    | 3         | 5.66%   |
| 2 x Intel      | 2         | 3.77%   |
| AMD + Nvidia   | 1         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 86.79%  |
| Proprietary | 4         | 7.55%   |
| Unknown     | 3         | 5.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 86.79%  |
| 0.01-0.5   | 7         | 13.21%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| LG Display           | 13        | 25.49%  |
| AU Optronics         | 10        | 19.61%  |
| Chimei Innolux       | 6         | 11.76%  |
| BOE                  | 5         | 9.8%    |
| Apple                | 5         | 9.8%    |
| Samsung Electronics  | 2         | 3.92%   |
| TMX                  | 1         | 1.96%   |
| Nvidia               | 1         | 1.96%   |
| LG Philips           | 1         | 1.96%   |
| Hewlett-Packard      | 1         | 1.96%   |
| HannStar             | 1         | 1.96%   |
| Fujitsu Siemens      | 1         | 1.96%   |
| Dell                 | 1         | 1.96%   |
| CPT                  | 1         | 1.96%   |
| BenQ                 | 1         | 1.96%   |
| Ancor Communications | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 3.92%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 3.92%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.96%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 1.96%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD0435 1600x900 310x170mm 13.9-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.96%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.96%   |
| Hewlett-Packard LCD Monitor HWP26A4 1440x900 410x260mm 19.1-inch      | 1         | 1.96%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.96%   |
| Fujitsu Siemens XE17-4 FUS0674 1280x1024 340x270mm 17.1-inch          | 1         | 1.96%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.96%   |
| CPT LCD Monitor COR17DB 1600x900 290x160mm 13.0-inch                  | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 340x190mm 15.3-inch      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch       | 1         | 1.96%   |
| BOE LCD Monitor BOE0872 1920x1080 340x190mm 15.3-inch                 | 1         | 1.96%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                 | 1         | 1.96%   |
| BOE LCD Monitor BOE06EE 1920x1080 310x170mm 13.9-inch                 | 1         | 1.96%   |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                  | 1         | 1.96%   |
| BOE LCD Monitor BOE0643 1920x1080 270x150mm 12.2-inch                 | 1         | 1.96%   |
| BenQ G610HDA BNQ7819 1366x768 340x190mm 15.3-inch                     | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 340x190mm 15.3-inch         | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 340x190mm 15.3-inch        | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO4100 1920x1200 220x140mm 10.3-inch        | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 34%     |
| 1366x768 (WXGA)    | 17        | 34%     |
| 1280x800 (WXGA)    | 5         | 10%     |
| 1600x900 (HD+)     | 4         | 8%      |
| 3840x2400          | 1         | 2%      |
| 3200x2000          | 1         | 2%      |
| 1920x1200 (WUXGA)  | 1         | 2%      |
| 1680x1050 (WSXGA+) | 1         | 2%      |
| 1440x900 (WXGA+)   | 1         | 2%      |
| 1280x1024 (SXGA)   | 1         | 2%      |
| 1024x600           | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 23        | 45.1%   |
| 13     | 14        | 27.45%  |
| 12     | 5         | 9.8%    |
| 17     | 2         | 3.92%   |
| 10     | 2         | 3.92%   |
| 24     | 1         | 1.96%   |
| 20     | 1         | 1.96%   |
| 19     | 1         | 1.96%   |
| 14     | 1         | 1.96%   |
| 11     | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 64.71%  |
| 201-300     | 14        | 27.45%  |
| 401-500     | 2         | 3.92%   |
| 501-600     | 1         | 1.96%   |
| 351-400     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 76%     |
| 16/10 | 11        | 22%     |
| 5/4   | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 18        | 35.29%  |
| 81-90          | 13        | 25.49%  |
| 61-70          | 4         | 7.84%   |
| 71-80          | 3         | 5.88%   |
| 101-110        | 3         | 5.88%   |
| 41-50          | 2         | 3.92%   |
| 151-200        | 2         | 3.92%   |
| 111-120        | 2         | 3.92%   |
| 51-60          | 1         | 1.96%   |
| 201-250        | 1         | 1.96%   |
| 141-150        | 1         | 1.96%   |
| 121-130        | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 43.14%  |
| 101-120       | 19        | 37.25%  |
| 51-100        | 5         | 9.8%    |
| 161-240       | 4         | 7.84%   |
| More than 240 | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 92.45%  |
| 2     | 2         | 3.77%   |
| 0     | 2         | 3.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 34        | 40.48%  |
| Realtek Semiconductor    | 18        | 21.43%  |
| Qualcomm Atheros         | 12        | 14.29%  |
| Broadcom                 | 8         | 9.52%   |
| Nvidia                   | 3         | 3.57%   |
| Marvell Technology Group | 2         | 2.38%   |
| Sierra Wireless          | 1         | 1.19%   |
| Samsung Electronics      | 1         | 1.19%   |
| Ralink Technology        | 1         | 1.19%   |
| Ralink                   | 1         | 1.19%   |
| Huawei Technologies      | 1         | 1.19%   |
| Google                   | 1         | 1.19%   |
| D-Link System            | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 11        | 11.34%  |
| Intel Wireless 7265                                                            | 7         | 7.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 6         | 6.19%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 4.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 3.09%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 3.09%   |
| Intel Wireless 8260                                                            | 3         | 3.09%   |
| Intel Wi-Fi 6 AX200                                                            | 3         | 3.09%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 3.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 2.06%   |
| Intel Wireless 3160                                                            | 2         | 2.06%   |
| Intel WiFi Link 5100                                                           | 2         | 2.06%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 2.06%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.06%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 2.06%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.06%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 2         | 2.06%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 2         | 2.06%   |
| Sierra Wireless EM7455                                                         | 1         | 1.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.03%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 1.03%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 1         | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 1.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.03%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.03%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.03%   |
| Intel Wireless 7260                                                            | 1         | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                                | 1         | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 56.36%  |
| Qualcomm Atheros      | 12        | 21.82%  |
| Broadcom              | 5         | 9.09%   |
| Realtek Semiconductor | 3         | 5.45%   |
| Sierra Wireless       | 1         | 1.82%   |
| Ralink Technology     | 1         | 1.82%   |
| Ralink                | 1         | 1.82%   |
| D-Link System         | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 7         | 12.73%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 10.91%  |
| Intel Wireless 8265 / 8275                                              | 4         | 7.27%   |
| Intel Wireless 8260                                                     | 3         | 5.45%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 5.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.64%   |
| Intel Wireless 3160                                                     | 2         | 3.64%   |
| Intel WiFi Link 5100                                                    | 2         | 3.64%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 3.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 3.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 3.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 3.64%   |
| Sierra Wireless EM7455                                                  | 1         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.82%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.82%   |
| Intel Wireless 7260                                                     | 1         | 1.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.82%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.82%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]    | 1         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 15        | 36.59%  |
| Intel                    | 14        | 34.15%  |
| Nvidia                   | 3         | 7.32%   |
| Broadcom                 | 3         | 7.32%   |
| Qualcomm Atheros         | 2         | 4.88%   |
| Marvell Technology Group | 2         | 4.88%   |
| Samsung Electronics      | 1         | 2.44%   |
| Google                   | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 11        | 26.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 7.32%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 7.32%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 7.32%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 4.88%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 4.88%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 4.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 4.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 2.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 2.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 2.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 2.44%   |
| Intel Ethernet Connection I219-V                                               | 1         | 2.44%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 2.44%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 54.84%  |
| Ethernet | 41        | 44.09%  |
| Modem    | 1         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 60%     |
| Ethernet | 22        | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 38        | 71.7%   |
| 1     | 14        | 26.42%  |
| 0     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 90.57%  |
| Yes  | 5         | 9.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 62.16%  |
| Apple                           | 4         | 10.81%  |
| Lite-On Technology              | 2         | 5.41%   |
| IMC Networks                    | 2         | 5.41%   |
| Qualcomm Atheros Communications | 1         | 2.7%    |
| Hewlett-Packard                 | 1         | 2.7%    |
| Cambridge Silicon Radio         | 1         | 2.7%    |
| Broadcom                        | 1         | 2.7%    |
| ASUSTek Computer                | 1         | 2.7%    |
| Alps Electric                   | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 35.9%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 5.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.13%   |
| Intel AX201 Bluetooth                               | 2         | 5.13%   |
| Intel AX200 Bluetooth                               | 2         | 5.13%   |
| Apple Built-in iSight (no firmware loaded)          | 2         | 5.13%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth       | 1         | 2.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.56%   |
| Intel AX210 Bluetooth                               | 1         | 2.56%   |
| IMC Networks Realtek Bluetooth Adapter              | 1         | 2.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.56%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 2.56%   |
| Apple Bluetooth Host Controller                     | 1         | 2.56%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 43        | 74.14%  |
| AMD                 | 7         | 12.07%  |
| Nvidia              | 5         | 8.62%   |
| XMOS                | 1         | 1.72%   |
| GN Netcom           | 1         | 1.72%   |
| C-Media Electronics | 1         | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 14.08%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 8.45%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 8.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.63%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 4.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.82%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.82%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.41%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.41%   |
| GN Netcom Jabra EVOLVE 20                                                                         | 1         | 1.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.41%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.41%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.41%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.41%   |
| Unknown                                                                                           | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 14        | 22.95%  |
| Samsung Electronics | 12        | 19.67%  |
| Unknown             | 7         | 11.48%  |
| Micron Technology   | 6         | 9.84%   |
| Kingston            | 6         | 9.84%   |
| Smart               | 2         | 3.28%   |
| Nanya Technology    | 2         | 3.28%   |
| A-DATA Technology   | 2         | 3.28%   |
| Transcend           | 1         | 1.64%   |
| Teikon              | 1         | 1.64%   |
| Smart Brazil        | 1         | 1.64%   |
| Ramaxel Technology  | 1         | 1.64%   |
| PNY                 | 1         | 1.64%   |
| GeIL                | 1         | 1.64%   |
| G.Skill             | 1         | 1.64%   |
| Elpida              | 1         | 1.64%   |
| Crucial             | 1         | 1.64%   |
| Unknown             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 4.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 2         | 3.13%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                   | 1         | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                 | 1         | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                 | 1         | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                  | 1         | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 1.56%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s                  | 1         | 1.56%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s        | 1         | 1.56%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s      | 1         | 1.56%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s       | 1         | 1.56%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s       | 1         | 1.56%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s      | 1         | 1.56%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                | 1         | 1.56%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                | 1         | 1.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.56%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.56%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.56%   |
| SK hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s      | 1         | 1.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 1.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 1.56%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1600MT/s         | 1         | 1.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 1         | 1.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 1.56%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s      | 1         | 1.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 1.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 1         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.56%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s     | 1         | 1.56%   |
| PNY RAM M4S16S682LJJJ43-12 16GB SODIMM DDR4 2667MT/s        | 1         | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 27        | 50.94%  |
| DDR4   | 19        | 35.85%  |
| DDR2   | 6         | 11.32%  |
| LPDDR3 | 1         | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 90.57%  |
| Row Of Chips | 3         | 5.66%   |
| DIMM         | 1         | 1.89%   |
| Unknown      | 1         | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 40.74%  |
| 2048  | 14        | 25.93%  |
| 8192  | 10        | 18.52%  |
| 16384 | 6         | 11.11%  |
| 32768 | 1         | 1.85%   |
| 1024  | 1         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 19        | 32.76%  |
| 2400    | 8         | 13.79%  |
| 1333    | 7         | 12.07%  |
| 2667    | 6         | 10.34%  |
| 3200    | 4         | 6.9%    |
| 2133    | 3         | 5.17%   |
| 1334    | 2         | 3.45%   |
| 1067    | 2         | 3.45%   |
| 800     | 2         | 3.45%   |
| 667     | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |
| 333     | 1         | 1.72%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 11        | 27.5%   |
| Microdia                      | 7         | 17.5%   |
| IMC Networks                  | 5         | 12.5%   |
| Sunplus Innovation Technology | 4         | 10%     |
| Realtek Semiconductor         | 4         | 10%     |
| Syntek                        | 2         | 5%      |
| Suyin                         | 2         | 5%      |
| Luxvisions Innotech Limited   | 1         | 2.5%    |
| Lite-On Technology            | 1         | 2.5%    |
| Apple                         | 1         | 2.5%    |
| Alcor Micro                   | 1         | 2.5%    |
| Acer                          | 1         | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                           | 3         | 7.5%    |
| Sunplus Integrated_Webcam_HD                                | 2         | 5%      |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 5%      |
| Microdia Integrated_Webcam_HD                               | 2         | 5%      |
| IMC Networks USB2.0 UVC VGA WebCam                          | 2         | 5%      |
| Chicony integrated camera                                   | 2         | 5%      |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera               | 1         | 2.5%    |
| Syntek Integrated Camera                                    | 1         | 2.5%    |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.5%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.5%    |
| Sunplus XiaoMi USB 2.0 Webcam                               | 1         | 2.5%    |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 2.5%    |
| Realtek Integrated_Webcam_HD                                | 1         | 2.5%    |
| Realtek HD WebCam                                           | 1         | 2.5%    |
| Microdia Webcam                                             | 1         | 2.5%    |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 2.5%    |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 2.5%    |
| Microdia Integrated Webcam HD                               | 1         | 2.5%    |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 2.5%    |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 2.5%    |
| Lite-On HP HD Webcam [Fixed]                                | 1         | 2.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 2.5%    |
| IMC Networks Integrated RGB Camera                          | 1         | 2.5%    |
| IMC Networks HD Camera                                      | 1         | 2.5%    |
| Chicony XiaoMi USB 2.0 Webcam                               | 1         | 2.5%    |
| Chicony VGA WebCam                                          | 1         | 2.5%    |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 2.5%    |
| Chicony TOSHIBA Web Camera - FHD                            | 1         | 2.5%    |
| Chicony Lenovo EasyCamera                                   | 1         | 2.5%    |
| Chicony 1.3M UVC Webcam                                     | 1         | 2.5%    |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 2.5%    |
| Alcor Micro Acer Integrated Webcam                          | 1         | 2.5%    |
| Acer Integrated Camera                                      | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 57.14%  |
| Synaptics        | 1         | 14.29%  |
| Broadcom         | 1         | 14.29%  |
| AuthenTec        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 28.57%  |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| AuthenTec AES1600                                                            | 1         | 14.29%  |
| Unknown                                                                      | 1         | 14.29%  |

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
| 1     | 18        | 33.96%  |
| 2     | 15        | 28.3%   |
| 3     | 9         | 16.98%  |
| 0     | 8         | 15.09%  |
| 4     | 2         | 3.77%   |
| 5     | 1         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 35        | 41.18%  |
| Bluetooth                | 24        | 28.24%  |
| Card reader              | 8         | 9.41%   |
| Fingerprint reader       | 7         | 8.24%   |
| Net/wireless             | 6         | 7.06%   |
| Sound                    | 2         | 2.35%   |
| Network                  | 2         | 2.35%   |
| Storage                  | 1         | 1.18%   |

