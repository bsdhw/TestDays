GhostBSD 21.08.27 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for GhostBSD 21.08.27.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GhostBSD_21.08.27/Desktop/README.md) and [notebooks](/Dist/GhostBSD_21.08.27/Notebook/README.md).

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

Total: 46

| Vendor     | Model                       | Form-Factor | Probe                                                     | Date         |
|------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek    | TUF GAMING X570-PRO         | Desktop     | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| MSI        | GE75 Raider 10SFS           | Notebook    | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| Apple      | MacBookPro11,4              | Notebook    | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Apple      | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [52f4bdd7d0](https://bsd-hardware.info/?probe=52f4bdd7d0) | Jan 21, 2022 |
| Supermicro | X10DRiB                     | Server      | [b4999ca89f](https://bsd-hardware.info/?probe=b4999ca89f) | Jan 21, 2022 |
| Dell       | 0NNNCT A01                  | Desktop     | [290f10c785](https://bsd-hardware.info/?probe=290f10c785) | Jan 21, 2022 |
| Dell       | Latitude E6540              | Notebook    | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu    | CELSIUS H780                | Notebook    | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | Notebook    | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| HP         | Laptop 15-dw2xxx            | Notebook    | [a6d7796cea](https://bsd-hardware.info/?probe=a6d7796cea) | Jan 13, 2022 |
| Dell       | Latitude 5510               | Notebook    | [a620d284cb](https://bsd-hardware.info/?probe=a620d284cb) | Jan 12, 2022 |
| Dell       | Inspiron N5110              | Notebook    | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Dell       | Latitude E5450              | Notebook    | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| Apple      | Mac-F22C86C8                | Mini pc     | [3ada7b4079](https://bsd-hardware.info/?probe=3ada7b4079) | Jan 03, 2022 |
| ASUSTek    | TUF GAMING FX504GD_FX80G... | Notebook    | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| Intel      | NUC7JYB J67970-400          | Mini pc     | [82c010f13c](https://bsd-hardware.info/?probe=82c010f13c) | Dec 09, 2021 |
| Alienware  | 01NYPT A00                  | Desktop     | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| ASUSTek    | X202E                       | Notebook    | [7f4e6f4541](https://bsd-hardware.info/?probe=7f4e6f4541) | Dec 05, 2021 |
| Fujitsu    | LIFEBOOK A555               | Notebook    | [c501c5c75e](https://bsd-hardware.info/?probe=c501c5c75e) | Dec 04, 2021 |
| Samsung    | 530XBB                      | Notebook    | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| ASUSTek    | PRIME Z270-K                | Desktop     | [a2270b6f09](https://bsd-hardware.info/?probe=a2270b6f09) | Dec 02, 2021 |
| Alienware  | m15 R4                      | Notebook    | [a724a7d7c7](https://bsd-hardware.info/?probe=a724a7d7c7) | Nov 29, 2021 |
| Lenovo     | ThinkPad T520 4243E51       | Notebook    | [82f5612822](https://bsd-hardware.info/?probe=82f5612822) | Nov 29, 2021 |
| Sony       | SVP13225SCBI                | Notebook    | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Dell       | Latitude 5510               | Notebook    | [3da78c9445](https://bsd-hardware.info/?probe=3da78c9445) | Nov 24, 2021 |
| Acer       | TravelMate B117-M           | Notebook    | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Toshiba    | Satellite C855-1U4          | Notebook    | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Medion     | MS-7728                     | Desktop     | [5b5a847fdd](https://bsd-hardware.info/?probe=5b5a847fdd) | Nov 02, 2021 |
| Dell       | Latitude D630               | Notebook    | [7e3a92badc](https://bsd-hardware.info/?probe=7e3a92badc) | Nov 02, 2021 |
| HP         | EliteBook Folio 1040 G3     | Notebook    | [d23636abb2](https://bsd-hardware.info/?probe=d23636abb2) | Oct 31, 2021 |
| MSI        | Modern 14 A10M              | Notebook    | [84838cd532](https://bsd-hardware.info/?probe=84838cd532) | Oct 07, 2021 |
| MSI        | Modern 14 A10M              | Notebook    | [db33045561](https://bsd-hardware.info/?probe=db33045561) | Oct 07, 2021 |
| Acer       | Aspire A315-56              | Notebook    | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| MSI        | Modern 14 A10M              | Notebook    | [277d8118da](https://bsd-hardware.info/?probe=277d8118da) | Sep 30, 2021 |
| Lenovo     | Flex 2-15 20405             | Notebook    | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| MSI        | Modern 14 A10M              | Notebook    | [103ccaf452](https://bsd-hardware.info/?probe=103ccaf452) | Sep 25, 2021 |
| Lenovo     | ThinkPad X220 4290W42       | Notebook    | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| ASUSTek    | SABERTOOTH X58              | Desktop     | [8f00f132de](https://bsd-hardware.info/?probe=8f00f132de) | Sep 23, 2021 |
| HUAWEI     | HLY-WX9XX                   | Notebook    | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Lenovo     | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo     | ThinkPad T400 6474E18       | Notebook    | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| HP         | EliteBook 8570p             | Notebook    | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| ASRock     | X570 Taichi                 | Desktop     | [9dc50c0bcb](https://bsd-hardware.info/?probe=9dc50c0bcb) | Sep 11, 2021 |
| Lenovo     | ThinkPad X250 20CL001GZA    | Notebook    | [ecd69774c0](https://bsd-hardware.info/?probe=ecd69774c0) | Sep 06, 2021 |
| System76   | Kudu                        | Notebook    | [c10fc12e40](https://bsd-hardware.info/?probe=c10fc12e40) | Sep 05, 2021 |
| Gigabyte   | Z77M-D3H                    | Desktop     | [d60f1bc575](https://bsd-hardware.info/?probe=d60f1bc575) | Aug 29, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 40        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| MATE     | 31        | 77.5%   |
| XFCE     | 6         | 15%     |
| LXQt     | 1         | 2.5%    |
| KDE5     | 1         | 2.5%    |
| Cinnamon | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 40        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 40        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| C     | 18        | 45%     |
| en_US | 17        | 42.5%   |
| de_DE | 4         | 10%     |
| pl_PL | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 90%     |
| BIOS | 4         | 10%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 38        | 95%     |
| Ufs  | 2         | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 40        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 15%     |
| ASUSTek Computer    | 6         | 15%     |
| Dell                | 5         | 12.5%   |
| MSI                 | 3         | 7.5%    |
| Hewlett-Packard     | 3         | 7.5%    |
| Apple               | 3         | 7.5%    |
| Fujitsu             | 2         | 5%      |
| Alienware           | 2         | 5%      |
| Acer                | 2         | 5%      |
| Toshiba             | 1         | 2.5%    |
| System76            | 1         | 2.5%    |
| Supermicro          | 1         | 2.5%    |
| Sony                | 1         | 2.5%    |
| Medion              | 1         | 2.5%    |
| HUAWEI              | 1         | 2.5%    |
| Gigabyte Technology | 1         | 2.5%    |
| ASRock              | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| MSI Modern 14 A10M                     | 2         | 5%      |
| Toshiba Satellite C855-1U4             | 1         | 2.5%    |
| System76 Kudu                          | 1         | 2.5%    |
| Supermicro X10DRi                      | 1         | 2.5%    |
| Sony SVP13225SCBI                      | 1         | 2.5%    |
| MSI GE75 Raider 10SFS                  | 1         | 2.5%    |
| Medion MS-7728                         | 1         | 2.5%    |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS     | 1         | 2.5%    |
| Lenovo ThinkPad X250 20CL001GZA        | 1         | 2.5%    |
| Lenovo ThinkPad X220 4290W42           | 1         | 2.5%    |
| Lenovo ThinkPad T520 4243E51           | 1         | 2.5%    |
| Lenovo ThinkPad T400 6474E18           | 1         | 2.5%    |
| Lenovo Flex 2-15 20405                 | 1         | 2.5%    |
| HUAWEI HLY-WX9XX                       | 1         | 2.5%    |
| HP Laptop 15-dw2xxx                    | 1         | 2.5%    |
| HP EliteBook Folio 1040 G3             | 1         | 2.5%    |
| HP EliteBook 8570p                     | 1         | 2.5%    |
| Gigabyte Z77M-D3H                      | 1         | 2.5%    |
| Fujitsu LIFEBOOK A555                  | 1         | 2.5%    |
| Fujitsu CELSIUS H780                   | 1         | 2.5%    |
| Dell Precision 3630 Tower              | 1         | 2.5%    |
| Dell Latitude E6540                    | 1         | 2.5%    |
| Dell Latitude D630                     | 1         | 2.5%    |
| Dell Latitude 5510                     | 1         | 2.5%    |
| Dell Inspiron N5110                    | 1         | 2.5%    |
| ASUS X202E                             | 1         | 2.5%    |
| ASUS VivoBook_ASUSLaptop X515UA_M515UA | 1         | 2.5%    |
| ASUS TUF GAMING X570-PRO               | 1         | 2.5%    |
| ASUS TUF GAMING FX504GD_FX80GD         | 1         | 2.5%    |
| ASUS SABERTOOTH X58                    | 1         | 2.5%    |
| ASUS PRIME Z270-K                      | 1         | 2.5%    |
| ASRock X570 Taichi                     | 1         | 2.5%    |
| Apple Macmini7,1                       | 1         | 2.5%    |
| Apple Macmini3,1                       | 1         | 2.5%    |
| Apple MacBookPro11,4                   | 1         | 2.5%    |
| Alienware m15 R4                       | 1         | 2.5%    |
| Alienware Aurora R5                    | 1         | 2.5%    |
| Acer TravelMate B117-M                 | 1         | 2.5%    |
| Acer Aspire A315-56                    | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 4         | 10%     |
| Dell Latitude      | 3         | 7.5%    |
| MSI Modern         | 2         | 5%      |
| HP EliteBook       | 2         | 5%      |
| ASUS TUF           | 2         | 5%      |
| Toshiba Satellite  | 1         | 2.5%    |
| System76 Kudu      | 1         | 2.5%    |
| Supermicro X10DRi  | 1         | 2.5%    |
| Sony SVP13225SCBI  | 1         | 2.5%    |
| MSI GE75           | 1         | 2.5%    |
| Medion MS-7728     | 1         | 2.5%    |
| Lenovo Yoga        | 1         | 2.5%    |
| Lenovo Flex        | 1         | 2.5%    |
| HUAWEI HLY-WX9XX   | 1         | 2.5%    |
| HP Laptop          | 1         | 2.5%    |
| Gigabyte Z77M-D3H  | 1         | 2.5%    |
| Fujitsu LIFEBOOK   | 1         | 2.5%    |
| Fujitsu CELSIUS    | 1         | 2.5%    |
| Dell Precision     | 1         | 2.5%    |
| Dell Inspiron      | 1         | 2.5%    |
| ASUS X202E         | 1         | 2.5%    |
| ASUS VivoBook      | 1         | 2.5%    |
| ASUS SABERTOOTH    | 1         | 2.5%    |
| ASUS PRIME         | 1         | 2.5%    |
| ASRock X570        | 1         | 2.5%    |
| Apple Macmini7     | 1         | 2.5%    |
| Apple Macmini3     | 1         | 2.5%    |
| Apple MacBookPro11 | 1         | 2.5%    |
| Alienware m15      | 1         | 2.5%    |
| Alienware Aurora   | 1         | 2.5%    |
| Acer TravelMate    | 1         | 2.5%    |
| Acer Aspire        | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 20%     |
| 2021 | 7         | 17.5%   |
| 2018 | 4         | 10%     |
| 2011 | 4         | 10%     |
| 2019 | 3         | 7.5%    |
| 2013 | 3         | 7.5%    |
| 2012 | 3         | 7.5%    |
| 2009 | 2         | 5%      |
| 2008 | 2         | 5%      |
| 2017 | 1         | 2.5%    |
| 2016 | 1         | 2.5%    |
| 2015 | 1         | 2.5%    |
| 2014 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 29        | 72.5%   |
| Desktop  | 8         | 20%     |
| Mini pc  | 2         | 5%      |
| Server   | 1         | 2.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 18        | 45%     |
| 16.01-24.0      | 9         | 22.5%   |
| 4.01-8.0        | 6         | 15%     |
| 32.01-64.0      | 5         | 12.5%   |
| More than 256.0 | 1         | 2.5%    |
| 64.01-256.0     | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 19        | 46.34%  |
| 0.51-1.0   | 11        | 26.83%  |
| 1.01-2.0   | 6         | 14.63%  |
| 4.01-8.0   | 2         | 4.88%   |
| 3.01-4.0   | 1         | 2.44%   |
| 24.01-32.0 | 1         | 2.44%   |
| 2.01-3.0   | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 51.22%  |
| 2      | 13        | 31.71%  |
| 0      | 5         | 12.2%   |
| 5      | 1         | 2.44%   |
| 3      | 1         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 55%     |
| Yes       | 18        | 45%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 80%     |
| No        | 8         | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 85%     |
| No        | 6         | 15%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 67.5%   |
| No        | 13        | 32.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 10        | 25%     |
| Germany      | 10        | 25%     |
| China        | 3         | 7.5%    |
| UK           | 2         | 5%      |
| Italy        | 2         | 5%      |
| Belgium      | 2         | 5%      |
| Switzerland  | 1         | 2.5%    |
| Sweden       | 1         | 2.5%    |
| Spain        | 1         | 2.5%    |
| South Africa | 1         | 2.5%    |
| Russia       | 1         | 2.5%    |
| Poland       | 1         | 2.5%    |
| Netherlands  | 1         | 2.5%    |
| Indonesia    | 1         | 2.5%    |
| India        | 1         | 2.5%    |
| France       | 1         | 2.5%    |
| Canada       | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Bonn           | 6         | 15%     |
| Wezeren        | 2         | 5%      |
| Denver         | 2         | 5%      |
| Zurich         | 1         | 2.5%    |
| Witbank        | 1         | 2.5%    |
| Whittier       | 1         | 2.5%    |
| Valencia       | 1         | 2.5%    |
| Traunstein     | 1         | 2.5%    |
| Toronto        | 1         | 2.5%    |
| Stiring-Wendel | 1         | 2.5%    |
| Staffanstorp   | 1         | 2.5%    |
| St Petersburg  | 1         | 2.5%    |
| Springfield    | 1         | 2.5%    |
| San Jose       | 1         | 2.5%    |
| Rome           | 1         | 2.5%    |
| New Delhi      | 1         | 2.5%    |
| Nanjing        | 1         | 2.5%    |
| Mystic         | 1         | 2.5%    |
| Murfreesboro   | 1         | 2.5%    |
| Madrid         | 1         | 2.5%    |
| Lingen         | 1         | 2.5%    |
| Knoxville      | 1         | 2.5%    |
| Jakarta        | 1         | 2.5%    |
| Hamburg        | 1         | 2.5%    |
| Dreieich       | 1         | 2.5%    |
| Doncaster      | 1         | 2.5%    |
| Cleveland      | 1         | 2.5%    |
| CheÅ‚mno    | 1         | 2.5%    |
| Brighton       | 1         | 2.5%    |
| Bologna        | 1         | 2.5%    |
| Bijie          | 1         | 2.5%    |
| Baiyun         | 1         | 2.5%    |
| Amsterdam      | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 34%     |
| WDC                 | 7         | 8      | 14%     |
| Seagate             | 7         | 8      | 14%     |
| Crucial             | 5         | 5      | 10%     |
| Kingston            | 4         | 4      | 8%      |
| Toshiba             | 3         | 3      | 6%      |
| Phison              | 1         | 2      | 2%      |
| KingSpec            | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| Hitachi             | 1         | 1      | 2%      |
| HGST                | 1         | 1      | 2%      |
| Goodram             | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston RBUSNS8154P3512GJ 512GB   | 2         | 3.85%   |
| WDC WDS480G2G0A-00JH30 480GB       | 1         | 1.92%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 1         | 1.92%   |
| WDC WD5000BEVT-24A0RT0 500GB       | 1         | 1.92%   |
| WDC WD2002FAEX-007BA0 2TB          | 1         | 1.92%   |
| WDC WD10JMVW-11AJGS1 1TB           | 1         | 1.92%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1         | 1.92%   |
| WDC WD1002FBYS-05A6B0 1TB          | 1         | 1.92%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 1         | 1.92%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1.92%   |
| Toshiba KBG30ZMV512G 512GB         | 1         | 1.92%   |
| Toshiba DT01ACA050 500GB           | 1         | 1.92%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1.92%   |
| Seagate ST500DM002-1SB10A 500GB    | 1         | 1.92%   |
| Seagate ST400FP0021 400GB          | 1         | 1.92%   |
| Seagate ST4000DM000-1F2168 4TB     | 1         | 1.92%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1.92%   |
| Seagate ST1500DL003-9VT16L 1.5TB   | 1         | 1.92%   |
| Seagate ST1000LM049-2GH172 1TB     | 1         | 1.92%   |
| Samsung SSD 980 PRO 500GB          | 1         | 1.92%   |
| Samsung SSD 970 EVO Plus 500GB     | 1         | 1.92%   |
| Samsung SSD 970 EVO Plus 1TB       | 1         | 1.92%   |
| Samsung SSD 970 EVO 500GB          | 1         | 1.92%   |
| Samsung SSD 860 QVO 2TB            | 1         | 1.92%   |
| Samsung SSD 860 EVO M.2 1TB        | 1         | 1.92%   |
| Samsung SSD 860 EVO 500GB          | 1         | 1.92%   |
| Samsung SSD 850 EVO 500GB          | 1         | 1.92%   |
| Samsung SSD 850 EVO 250GB          | 1         | 1.92%   |
| Samsung SSD 840 PRO Series 256GB   | 1         | 1.92%   |
| Samsung SSD 840 EVO 500GB          | 1         | 1.92%   |
| Samsung PM9A1 NVMe 512GB           | 1         | 1.92%   |
| Samsung MZVLQ512HALU-00000 512GB   | 1         | 1.92%   |
| Samsung MZVLQ256HAJD-000H1 256GB   | 1         | 1.92%   |
| Samsung MZVLB512HAJQ-00000 512GB   | 1         | 1.92%   |
| Samsung MZNTE128HMGR-000SO 128GB   | 1         | 1.92%   |
| Samsung MZNLN512HAJQ-00007 512GB   | 1         | 1.92%   |
| Samsung MZMPA024HMCD-000L1 24GB    | 1         | 1.92%   |
| Phison Sabrent Rocket 4.0 2TB      | 1         | 1.92%   |
| Kingston SV300S37A240G 240GB       | 1         | 1.92%   |
| Kingston SV300S37A120G 120GB       | 1         | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 7      | 37.5%   |
| Seagate | 6         | 7      | 37.5%   |
| Toshiba | 2         | 2      | 12.5%   |
| Hitachi | 1         | 1      | 6.25%   |
| HGST    | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 47.62%  |
| Crucial             | 4         | 4      | 19.05%  |
| Kingston            | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| Seagate             | 1         | 1      | 4.76%   |
| KingSpec            | 1         | 1      | 4.76%   |
| Goodram             | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 19        | 21     | 42.22%  |
| NVMe | 13        | 17     | 28.89%  |
| HDD  | 13        | 18     | 28.89%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 39     | 68.29%  |
| NVMe | 13        | 17     | 31.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 22     | 58.82%  |
| 0.51-1.0   | 9         | 11     | 26.47%  |
| 1.01-2.0   | 4         | 4      | 11.76%  |
| 3.01-4.0   | 1         | 2      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 19        | 46.34%  |
| 251-500    | 5         | 12.2%   |
| 501-1000   | 5         | 12.2%   |
| 51-100     | 4         | 9.76%   |
| 1001-2000  | 3         | 7.32%   |
| 101-250    | 2         | 4.88%   |
| Unknown    | 2         | 4.88%   |
| 21-50      | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 36        | 87.8%   |
| 21-50   | 3         | 7.32%   |
| Unknown | 2         | 4.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 25%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 25%     |
| Crucial CT1000MX500SSD1 1TB                  | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| HGST                | 1         | 1      | 25%     |
| Crucial             | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 50%     |
| HDD  | 2         | 2      | 50%     |

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


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 35        | 52     | 89.74%  |
| Malfunc | 4         | 4      | 10.26%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 30        | 60%     |
| Samsung Electronics         | 8         | 16%     |
| AMD                         | 3         | 6%      |
| Kingston Technology Company | 2         | 4%      |
| Toshiba                     | 1         | 2%      |
| Phison Electronics          | 1         | 2%      |
| Nvidia                      | 1         | 2%      |
| Micron/Crucial Technology   | 1         | 2%      |
| Marvell Technology Group    | 1         | 2%      |
| JMicron Technology          | 1         | 2%      |
| Broadcom / LSI              | 1         | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 5.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 5.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 5.66%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 5.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 3.77%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 3.77%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                   | 2         | 3.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 3.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 3.77%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                   | 1         | 1.89%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 1.89%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.89%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.89%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                         | 1         | 1.89%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1         | 1.89%   |
| JMicron JMB362 SATA Controller                                                   | 1         | 1.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.89%   |
| Intel SSD 660P Series                                                            | 1         | 1.89%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.89%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.89%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1         | 1.89%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.89%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1         | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 1.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 1.89%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 1         | 1.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 33        | 64.71%  |
| NVMe | 13        | 25.49%  |
| RAID | 3         | 5.88%   |
| IDE  | 2         | 3.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 87.5%   |
| AMD    | 5         | 12.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 5%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 5%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 5%      |
| Intel Xeon E-2236 CPU @ 3.40GHz               | 1         | 2.5%    |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz           | 1         | 2.5%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 2.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 2.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 2.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.5%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 2.5%    |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 2.5%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 2.5%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 2.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1         | 2.5%    |
| Intel Core i7 CPU 950 @ 3.07GHz               | 1         | 2.5%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 2.5%    |
| Intel Core i5-4278U CPU @ 2.60GHz             | 1         | 2.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-3570 CPU @ 3.40GHz              | 1         | 2.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.5%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 2.5%    |
| Intel Core i5-10310U CPU @ 1.70GHz            | 1         | 2.5%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.5%    |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 2.5%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 2.5%    |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 1         | 2.5%    |
| Intel Core 2 Duo                              | 1         | 2.5%    |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 2.5%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 2.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.5%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 13        | 32.5%   |
| Intel Core i5    | 11        | 27.5%   |
| Intel Core i3    | 3         | 7.5%    |
| Intel Core 2 Duo | 3         | 7.5%    |
| Intel Xeon       | 2         | 5%      |
| Intel Core i9    | 2         | 5%      |
| AMD Ryzen 7      | 2         | 5%      |
| AMD Ryzen 5      | 2         | 5%      |
| Intel Celeron    | 1         | 2.5%    |
| AMD Ryzen 9      | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 14        | 35%     |
| 2       | 13        | 32.5%   |
| 8       | 3         | 7.5%    |
| 6       | 3         | 7.5%    |
| 24      | 2         | 5%      |
| 16      | 2         | 5%      |
| Unknown | 2         | 5%      |
| 12      | 1         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 95%     |
| 2      | 2         | 5%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 30        | 75%     |
| 1       | 8         | 20%     |
| Unknown | 2         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 17.5%   |
| Haswell     | 5         | 12.5%   |
| SandyBridge | 4         | 10%     |
| IvyBridge   | 4         | 10%     |
| Zen 3       | 3         | 7.5%    |
| Skylake     | 3         | 7.5%    |
| Broadwell   | 3         | 7.5%    |
| Penryn      | 2         | 5%      |
| IceLake     | 2         | 5%      |
| CometLake   | 2         | 5%      |
| Zen+        | 1         | 2.5%    |
| Silvermont  | 1         | 2.5%    |
| Nehalem     | 1         | 2.5%    |
| Core        | 1         | 2.5%    |
| Unknown     | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 27        | 54%     |
| Nvidia            | 13        | 26%     |
| AMD               | 9         | 18%     |
| ASPEED Technology | 1         | 2%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 5.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 3.92%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.92%   |
| Intel HD Graphics 530                                                                    | 2         | 3.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 3.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 3.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 3.92%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 1.96%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 1.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.96%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.96%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.96%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 1.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.96%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1         | 1.96%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 1.96%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.96%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.96%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.96%   |
| Intel HD Graphics 630                                                                    | 1         | 1.96%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.96%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 1.96%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                                  | 1         | 1.96%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.96%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.96%   |
| AMD Lucienne                                                                             | 1         | 1.96%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.96%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 1         | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 16        | 40%     |
| Intel + Nvidia  | 8         | 20%     |
| 1 x AMD         | 8         | 20%     |
| 1 x Nvidia      | 4         | 10%     |
| 2 x Intel       | 2         | 5%      |
| Nvidia + ASPEED | 1         | 2.5%    |
| Intel + AMD     | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 80%     |
| Proprietary | 8         | 20%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 85%     |
| 0.51-1.0   | 4         | 10%     |
| 7.01-8.0   | 1         | 2.5%    |
| 1.01-2.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 8         | 22.22%  |
| Chimei Innolux       | 6         | 16.67%  |
| LG Display           | 5         | 13.89%  |
| Samsung Electronics  | 3         | 8.33%   |
| Dell                 | 3         | 8.33%   |
| Lenovo               | 2         | 5.56%   |
| Panasonic            | 1         | 2.78%   |
| Mi                   | 1         | 2.78%   |
| Hewlett-Packard      | 1         | 2.78%   |
| Fujitsu Siemens      | 1         | 2.78%   |
| BenQ                 | 1         | 2.78%   |
| ASUSTek Computer     | 1         | 2.78%   |
| Apple                | 1         | 2.78%   |
| AOC                  | 1         | 2.78%   |
| Ancor Communications | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 5.56%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 1         | 2.78%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch   | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch  | 1         | 2.78%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch           | 1         | 2.78%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                  | 1         | 2.78%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 2.78%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 2.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 2.78%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 2.78%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 1         | 2.78%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 2.78%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch           | 1         | 2.78%   |
| Fujitsu Siemens P24-9 TE FUS08B8 1920x1080 530x300mm 24.0-inch        | 1         | 2.78%   |
| Dell U2711 DELA057 2560x1440 600x340mm 27.2-inch                      | 1         | 2.78%   |
| Dell U2312HM DEL4073 1920x1080 510x290mm 23.1-inch                    | 1         | 2.78%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                    | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch      | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch      | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 1         | 2.78%   |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                     | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO80EC 1366x768 340x190mm 15.3-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO509D 1920x1080 380x220mm 17.3-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO35EC 1366x768 340x190mm 15.3-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch         | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO26ED 1920x1080 340x190mm 15.3-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO119D 1920x1080 380x210mm 17.1-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO1136 2560x1440 310x170mm 13.9-inch        | 1         | 2.78%   |
| ASUSTek Computer VG259 AUS25A6 1920x1080 540x300mm 24.3-inch          | 1         | 2.78%   |
| Apple Color LCD APPA02E 2880x1800 330x210mm 15.4-inch                 | 1         | 2.78%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                    | 1         | 2.78%   |
| Ancor Communications ASUS VH222 ACI22AB 1920x1080 470x260mm 21.1-inch | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 18        | 50%     |
| 1366x768 (WXGA)    | 8         | 22.22%  |
| 2560x1440 (QHD)    | 3         | 8.33%   |
| 3840x2160 (4K)     | 2         | 5.56%   |
| 2880x1800          | 1         | 2.78%   |
| 1680x1050 (WSXGA+) | 1         | 2.78%   |
| 1600x900 (HD+)     | 1         | 2.78%   |
| 1440x900 (WXGA+)   | 1         | 2.78%   |
| 1280x800 (WXGA)    | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 11        | 30.56%  |
| 27     | 4         | 11.11%  |
| 24     | 4         | 11.11%  |
| 17     | 3         | 8.33%   |
| 13     | 3         | 8.33%   |
| 14     | 2         | 5.56%   |
| 12     | 2         | 5.56%   |
| 11     | 2         | 5.56%   |
| 23     | 1         | 2.78%   |
| 22     | 1         | 2.78%   |
| 21     | 1         | 2.78%   |
| 19     | 1         | 2.78%   |
| 16     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 38.89%  |
| 501-600     | 8         | 22.22%  |
| 201-300     | 6         | 16.67%  |
| 351-400     | 4         | 11.11%  |
| 401-500     | 3         | 8.33%   |
| 601-700     | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 88.57%  |
| 16/10 | 4         | 11.43%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 9         | 25%     |
| 81-90          | 5         | 13.89%  |
| 201-250        | 5         | 13.89%  |
| 301-350        | 4         | 11.11%  |
| 121-130        | 3         | 8.33%   |
| 61-70          | 2         | 5.56%   |
| 51-60          | 2         | 5.56%   |
| 151-200        | 2         | 5.56%   |
| 101-110        | 2         | 5.56%   |
| 251-300        | 1         | 2.78%   |
| 111-120        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 48.57%  |
| 51-100        | 9         | 25.71%  |
| 101-120       | 6         | 17.14%  |
| 161-240       | 2         | 5.71%   |
| More than 240 | 1         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 77.5%   |
| 0     | 7         | 17.5%   |
| 2     | 2         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 25        | 45.45%  |
| Realtek Semiconductor             | 12        | 21.82%  |
| Qualcomm Atheros                  | 8         | 14.55%  |
| Broadcom                          | 4         | 7.27%   |
| ASUSTek Computer                  | 2         | 3.64%   |
| Nvidia                            | 1         | 1.82%   |
| Hewlett-Packard                   | 1         | 1.82%   |
| Ericsson Business Mobile Networks | 1         | 1.82%   |
| Edimax Technology                 | 1         | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 9.59%   |
| Intel Wireless 7265                                               | 3         | 4.11%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 4.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 4.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.74%   |
| Intel Wireless 8260                                               | 2         | 2.74%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 2         | 2.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.37%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 1.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.37%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.37%   |
| Intel Wireless 7260                                               | 1         | 1.37%   |
| Intel Wireless 3165                                               | 1         | 1.37%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.37%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 1.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.37%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.37%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.37%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.37%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.37%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 57.89%  |
| Realtek Semiconductor | 5         | 13.16%  |
| Qualcomm Atheros      | 5         | 13.16%  |
| Broadcom              | 3         | 7.89%   |
| ASUSTek Computer      | 2         | 5.26%   |
| Edimax Technology     | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                | 3         | 7.89%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 7.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 7.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 7.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 2         | 5.26%   |
| Intel Wireless 8260                                                | 2         | 5.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 2         | 5.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 1         | 2.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1         | 2.63%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                    | 1         | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1         | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 1         | 2.63%   |
| Intel Wireless 7260                                                | 1         | 2.63%   |
| Intel Wireless 3165                                                | 1         | 2.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection            | 1         | 2.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 1         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 1         | 2.63%   |
| Intel Centrino Ultimate-N 6300                                     | 1         | 2.63%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]  | 1         | 2.63%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 1         | 2.63%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter       | 1         | 2.63%   |
| Broadcom BCM4321 802.11a/b/g/n                                     | 1         | 2.63%   |
| ASUS WL-167G v1 802.11g Adapter [Ralink RT2571]                    | 1         | 2.63%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 46.88%  |
| Realtek Semiconductor | 10        | 31.25%  |
| Qualcomm Atheros      | 4         | 12.5%   |
| Broadcom              | 2         | 6.25%   |
| Nvidia                | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 21.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 6.06%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 2         | 6.06%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 3.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.03%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 3.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 3.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.03%   |
| Nvidia MCP79 Ethernet                                             | 1         | 3.03%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 3.03%   |
| Intel I350 Gigabit Network Connection                             | 1         | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.03%   |
| Intel Ethernet Controller I225-V                                  | 1         | 3.03%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 3.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.03%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 3.03%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 3.03%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.03%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 50%     |
| Ethernet | 32        | 47.06%  |
| Modem    | 2         | 2.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 32        | 57.14%  |
| WiFi     | 22        | 39.29%  |
| Modem    | 2         | 3.57%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 27        | 67.5%   |
| 1     | 12        | 30%     |
| 4     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 97.5%   |
| Yes  | 1         | 2.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 64.29%  |
| IMC Networks          | 3         | 10.71%  |
| Apple                 | 3         | 10.71%  |
| Realtek Semiconductor | 2         | 7.14%   |
| Toshiba               | 1         | 3.57%   |
| Lite-On Technology    | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 8         | 28.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 14.29%  |
| Intel AX201 Bluetooth                             | 3         | 10.71%  |
| Intel AX200 Bluetooth                             | 3         | 10.71%  |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 2         | 7.14%   |
| Apple Bluetooth Host Controller                   | 2         | 7.14%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip   | 1         | 3.57%   |
| Realtek RTL8723B Bluetooth                        | 1         | 3.57%   |
| Realtek Bluetooth Adapter                         | 1         | 3.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 3.57%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1       | 1         | 3.57%   |
| Apple Bluetooth USB Host Controller               | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 58.18%  |
| Nvidia              | 10        | 18.18%  |
| AMD                 | 9         | 16.36%  |
| C-Media Electronics | 2         | 3.64%   |
| VIA Technologies    | 1         | 1.82%   |
| Logitech            | 1         | 1.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 6.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 6.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 4.55%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 4.55%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 4.55%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 4.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 4.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 3.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 3.03%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 3.03%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 3.03%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 3.03%   |
| VIA Technologies USB Audio Device                                                                 | 1         | 1.52%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 1.52%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.52%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.52%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.52%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 1.52%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.52%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.52%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.52%   |
| Logitech G935/G933s Gaming Headset                                                                | 1         | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.52%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.52%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.52%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1         | 1.52%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 1         | 1.52%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.52%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.52%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 32.65%  |
| SK hynix            | 11        | 22.45%  |
| Micron Technology   | 5         | 10.2%   |
| Unknown             | 2         | 4.08%   |
| Kingston            | 2         | 4.08%   |
| Crucial             | 2         | 4.08%   |
| Unknown             | 2         | 4.08%   |
| Unknown (ABCD)      | 1         | 2.04%   |
| Transcend           | 1         | 2.04%   |
| Nanya Technology    | 1         | 2.04%   |
| Kingmax             | 1         | 2.04%   |
| GOODRAM             | 1         | 2.04%   |
| G.Skill             | 1         | 2.04%   |
| Elpida              | 1         | 2.04%   |
| Corsair             | 1         | 2.04%   |
| 09490000802C        | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 10%     |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 4%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 4%      |
| Unknown                                                          | 2         | 4%      |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 2%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2%      |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 667MT/s                | 1         | 2%      |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2%      |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 2%      |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 2%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2%      |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 2%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2%      |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2%      |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s    | 1         | 2%      |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 2%      |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2%      |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 2%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2%      |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2%      |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 2%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 1         | 2%      |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 2%      |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2%      |
| Samsung RAM M391A4G43MB1-CTD 32GB DIMM DDR4 3200MT/s             | 1         | 2%      |
| Nanya RAM M2F4G64CB8HB5N-CG 4GB DIMM DDR3 1333MT/s               | 1         | 2%      |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 2%      |
| Micron RAM Module 4GB SODIMM DDR4 2133MT/s                       | 1         | 2%      |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2%      |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s            | 1         | 2%      |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s              | 1         | 2%      |
| Kingston RAM Module 4GB SODIMM DDR4 2667MT/s                     | 1         | 2%      |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 2400MT/s            | 1         | 2%      |
| Kingmax RAM FLFF65F-C8KL9 4GB DIMM DDR3 1333MT/s                 | 1         | 2%      |
| GOODRAM RAM GR1333S364L9S/4G 4GB SODIMM DDR3 1333MT/s            | 1         | 2%      |
| G.Skill RAM F4-4000C18-8GTZ 8GB DIMM DDR4 3333MT/s               | 1         | 2%      |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 2%      |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 19        | 46.34%  |
| DDR3    | 19        | 46.34%  |
| LPDDR4  | 1         | 2.44%   |
| DDR2    | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 70.73%  |
| DIMM         | 9         | 21.95%  |
| Row Of Chips | 3         | 7.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 18        | 40.91%  |
| 8192  | 14        | 31.82%  |
| 16384 | 5         | 11.36%  |
| 2048  | 5         | 11.36%  |
| 32768 | 2         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 10        | 22.73%  |
| 2667    | 9         | 20.45%  |
| 3200    | 5         | 11.36%  |
| 2133    | 4         | 9.09%   |
| 1333    | 4         | 9.09%   |
| 1334    | 3         | 6.82%   |
| 2400    | 2         | 4.55%   |
| 3600    | 1         | 2.27%   |
| 3333    | 1         | 2.27%   |
| 1867    | 1         | 2.27%   |
| 1067    | 1         | 2.27%   |
| 1066    | 1         | 2.27%   |
| 667     | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

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


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 4         | 21.05%  |
| Realtek Semiconductor | 3         | 15.79%  |
| Quanta                | 3         | 15.79%  |
| IMC Networks          | 3         | 15.79%  |
| Microdia              | 2         | 10.53%  |
| Logitech              | 2         | 10.53%  |
| Bison Electronics     | 2         | 10.53%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD         | 2         | 10.53%  |
| Realtek Front Camera                 | 1         | 5.26%   |
| Quanta VGA WebCam                    | 1         | 5.26%   |
| Quanta Realtek PC Camera             | 1         | 5.26%   |
| Quanta HP TrueVision HD Camera       | 1         | 5.26%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 5.26%   |
| Microdia Integrated Webcam           | 1         | 5.26%   |
| Logitech HD Pro Webcam C920          | 1         | 5.26%   |
| Logitech C920 HD Pro Webcam          | 1         | 5.26%   |
| IMC Networks USB 2.0 UVC HD Webcam   | 1         | 5.26%   |
| IMC Networks Realtek DMFT RGB        | 1         | 5.26%   |
| IMC Networks Integrated Camera       | 1         | 5.26%   |
| Chicony Integrated HP HD Webcam      | 1         | 5.26%   |
| Chicony Integrated Camera            | 1         | 5.26%   |
| Chicony HP HD Camera                 | 1         | 5.26%   |
| Chicony HD WebCam                    | 1         | 5.26%   |
| Bison Lenovo EasyCamera              | 1         | 5.26%   |
| Bison Integrated Camera              | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 33.33%  |
| Next Biometrics  | 1         | 33.33%  |
| Broadcom         | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 33.33%  |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |

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
| 2     | 15        | 37.5%   |
| 1     | 14        | 35%     |
| 4     | 5         | 12.5%   |
| 3     | 4         | 10%     |
| 5     | 1         | 2.5%    |
| 0     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 29        | 37.66%  |
| Net/wireless             | 18        | 23.38%  |
| Bluetooth                | 17        | 22.08%  |
| Card reader              | 5         | 6.49%   |
| Fingerprint reader       | 4         | 5.19%   |
| Sound                    | 2         | 2.6%    |
| Firewire controller      | 2         | 2.6%    |

