NomadBSD 20221130 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for NomadBSD 20221130.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NomadBSD_20221130/Desktop/README.md) and [notebooks](/Dist/NomadBSD_20221130/Notebook/README.md).

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

Total: 38

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek       | 1005PXD                     | Notebook    | [1b05e8cf1b](https://bsd-hardware.info/?probe=1b05e8cf1b) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [e732d89b06](https://bsd-hardware.info/?probe=e732d89b06) | Sep 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [8816b1ac4a](https://bsd-hardware.info/?probe=8816b1ac4a) | Sep 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [714516a696](https://bsd-hardware.info/?probe=714516a696) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [cac0950717](https://bsd-hardware.info/?probe=cac0950717) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [3c69dd7003](https://bsd-hardware.info/?probe=3c69dd7003) | Sep 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | Notebook    | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| eMachines     | G640                        | Notebook    | [c05619033c](https://bsd-hardware.info/?probe=c05619033c) | Sep 14, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| Lenovo        | ThinkPad X230 2325IB1       | Notebook    | [41fbf7d1ca](https://bsd-hardware.info/?probe=41fbf7d1ca) | Aug 26, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [66f982c40b](https://bsd-hardware.info/?probe=66f982c40b) | Aug 23, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [7a5d32eb7f](https://bsd-hardware.info/?probe=7a5d32eb7f) | Jul 29, 2023 |
| HP            | EliteBook 750 G1            | Notebook    | [e0af4797d4](https://bsd-hardware.info/?probe=e0af4797d4) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | Notebook    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| ASRockRack    | C226M WS                    | Desktop     | [06a8ca514a](https://bsd-hardware.info/?probe=06a8ca514a) | Apr 14, 2023 |
| ECS           | Z77H2-AX                    | Desktop     | [32a290eb5f](https://bsd-hardware.info/?probe=32a290eb5f) | Apr 13, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | Notebook    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Dell          | Latitude 7300               | Notebook    | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [04f43c3d70](https://bsd-hardware.info/?probe=04f43c3d70) | Feb 23, 2023 |
| Acer          | Aspire 7738                 | Notebook    | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | Notebook    | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| HP            | 1589                        | Desktop     | [8a927b43cb](https://bsd-hardware.info/?probe=8a927b43cb) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 31        | 96.88%  |
| i386  | 1         | 3.13%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 22        | 68.75%  |
| xinitrc       | 6         | 18.75%  |
| KDE5          | 2         | 6.25%   |
| Enlightenment | 2         | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 32        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 30        | 93.75%  |
| LightDM | 2         | 6.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 9         | 28.13%  |
| en_GB   | 5         | 15.63%  |
| zh_TW   | 4         | 12.5%   |
| fr_FR   | 4         | 12.5%   |
| fi_FI   | 3         | 9.38%   |
| Unknown | 3         | 9.38%   |
| sv_SE   | 1         | 3.13%   |
| ru_RU   | 1         | 3.13%   |
| lt_LT   | 1         | 3.13%   |
| bg_BG   | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 32        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 18        | 56.25%  |
| Zfs  | 14        | 43.75%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 18        | 56.25%  |
| MBR  | 14        | 43.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 37.5%   |
| ASUSTek Computer    | 3         | 9.38%   |
| Hewlett-Packard     | 2         | 6.25%   |
| Dell                | 2         | 6.25%   |
| Apple               | 2         | 6.25%   |
| Acer                | 2         | 6.25%   |
| Samsung Electronics | 1         | 3.13%   |
| Gigabyte Technology | 1         | 3.13%   |
| Fujitsu Siemens     | 1         | 3.13%   |
| Fujitsu             | 1         | 3.13%   |
| eMachines           | 1         | 3.13%   |
| ECS                 | 1         | 3.13%   |
| Chuwi               | 1         | 3.13%   |
| ASRockRack          | 1         | 3.13%   |
| ASRock              | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung N150/N210/N220                   | 1         | 3.13%   |
| Lenovo Yoga 710-11IKB 80V6               | 1         | 3.13%   |
| Lenovo ThinkPad X280 20KESB4T00          | 1         | 3.13%   |
| Lenovo ThinkPad X230 2325IB1             | 1         | 3.13%   |
| Lenovo ThinkPad X230 23255NG             | 1         | 3.13%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT | 1         | 3.13%   |
| Lenovo ThinkPad W520 42844DG             | 1         | 3.13%   |
| Lenovo ThinkPad T470 20HES0EV0A          | 1         | 3.13%   |
| Lenovo ThinkPad T16 Gen 2 21HHCTO1WW     | 1         | 3.13%   |
| Lenovo ThinkPad E495 20NE000BSP          | 1         | 3.13%   |
| Lenovo ThinkPad E14 20RA0036RT           | 1         | 3.13%   |
| Lenovo ThinkCentre M93p 10AAS4EN00       | 1         | 3.13%   |
| Lenovo G50-70 20351                      | 1         | 3.13%   |
| HP Z420 Workstation                      | 1         | 3.13%   |
| HP EliteBook 750 G1                      | 1         | 3.13%   |
| Gigabyte H61M-S1                         | 1         | 3.13%   |
| Fujitsu Siemens AMILO Li3710             | 1         | 3.13%   |
| Fujitsu CELSIUS H730                     | 1         | 3.13%   |
| eMachines G640                           | 1         | 3.13%   |
| ECS Z77H2-AX                             | 1         | 3.13%   |
| Dell XPS 13 7390                         | 1         | 3.13%   |
| Dell Latitude 7300                       | 1         | 3.13%   |
| Chuwi CoreBook X                         | 1         | 3.13%   |
| ASUS ROG STRIX B550-F GAMING             | 1         | 3.13%   |
| ASUS K40IN                               | 1         | 3.13%   |
| ASUS 1005PXD                             | 1         | 3.13%   |
| ASRockRack C226M WS                      | 1         | 3.13%   |
| ASRock N68-S UCC                         | 1         | 3.13%   |
| Apple MacBookPro7,1                      | 1         | 3.13%   |
| Apple MacBookPro14,1                     | 1         | 3.13%   |
| Acer Swift SF314-56                      | 1         | 3.13%   |
| Acer Aspire 7738                         | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9         | 28.13%  |
| Samsung N150          | 1         | 3.13%   |
| Lenovo Yoga           | 1         | 3.13%   |
| Lenovo ThinkCentre    | 1         | 3.13%   |
| Lenovo G50-70         | 1         | 3.13%   |
| HP Z420               | 1         | 3.13%   |
| HP EliteBook          | 1         | 3.13%   |
| Gigabyte H61M-S1      | 1         | 3.13%   |
| Fujitsu Siemens AMILO | 1         | 3.13%   |
| Fujitsu CELSIUS       | 1         | 3.13%   |
| eMachines G640        | 1         | 3.13%   |
| ECS Z77H2-AX          | 1         | 3.13%   |
| Dell XPS              | 1         | 3.13%   |
| Dell Latitude         | 1         | 3.13%   |
| Chuwi CoreBook        | 1         | 3.13%   |
| ASUS ROG              | 1         | 3.13%   |
| ASUS K40IN            | 1         | 3.13%   |
| ASUS 1005PXD          | 1         | 3.13%   |
| ASRockRack C226M      | 1         | 3.13%   |
| ASRock N68-S          | 1         | 3.13%   |
| Apple MacBookPro7     | 1         | 3.13%   |
| Apple MacBookPro14    | 1         | 3.13%   |
| Acer Swift            | 1         | 3.13%   |
| Acer Aspire           | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 4         | 12.5%   |
| 2012 | 4         | 12.5%   |
| 2022 | 3         | 9.38%   |
| 2020 | 3         | 9.38%   |
| 2011 | 3         | 9.38%   |
| 2023 | 2         | 6.25%   |
| 2018 | 2         | 6.25%   |
| 2015 | 2         | 6.25%   |
| 2013 | 2         | 6.25%   |
| 2010 | 2         | 6.25%   |
| 2009 | 2         | 6.25%   |
| 2021 | 1         | 3.13%   |
| 2016 | 1         | 3.13%   |
| 2014 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 25        | 78.13%  |
| Desktop  | 7         | 21.88%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 96.88%  |
| Yes  | 1         | 3.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 13        | 40.63%  |
| 16.01-24.0 | 9         | 28.13%  |
| 4.01-8.0   | 3         | 9.38%   |
| 32.01-64.0 | 3         | 9.38%   |
| 2.01-3.0   | 3         | 9.38%   |
| 24.01-32.0 | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 15        | 46.88%  |
| 0.51-1.0 | 12        | 37.5%   |
| 1.01-2.0 | 4         | 12.5%   |
| 2.01-3.0 | 1         | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 22        | 68.75%  |
| 2      | 5         | 15.63%  |
| 0      | 3         | 9.38%   |
| 4      | 1         | 3.13%   |
| 3      | 1         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 75%     |
| Yes       | 8         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 78.13%  |
| No        | 7         | 21.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 81.25%  |
| No        | 6         | 18.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 56.25%  |
| No        | 14        | 43.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| France      | 6         | 18.75%  |
| USA         | 5         | 15.63%  |
| UK          | 5         | 15.63%  |
| Taiwan      | 4         | 12.5%   |
| Finland     | 3         | 9.38%   |
| Russia      | 2         | 6.25%   |
| Sweden      | 1         | 3.13%   |
| Spain       | 1         | 3.13%   |
| San Marino  | 1         | 3.13%   |
| Netherlands | 1         | 3.13%   |
| Lithuania   | 1         | 3.13%   |
| Bulgaria    | 1         | 3.13%   |
| Argentina   | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Taipei               | 3         | 9.38%   |
| Urcuit               | 2         | 6.25%   |
| Turku                | 2         | 6.25%   |
| Moscow               | 2         | 6.25%   |
| Melun                | 2         | 6.25%   |
| Lutherville-Timonium | 2         | 6.25%   |
| West Bromwich        | 1         | 3.13%   |
| Wakefield            | 1         | 3.13%   |
| Vilnius              | 1         | 3.13%   |
| Vaasa                | 1         | 3.13%   |
| Taichung             | 1         | 3.13%   |
| Sofia                | 1         | 3.13%   |
| Södertälje         | 1         | 3.13%   |
| Seattle              | 1         | 3.13%   |
| Sartrouville         | 1         | 3.13%   |
| San Marino           | 1         | 3.13%   |
| Saint-Raphaël       | 1         | 3.13%   |
| Rubí                | 1         | 3.13%   |
| Portland             | 1         | 3.13%   |
| Lincoln              | 1         | 3.13%   |
| Leesburg             | 1         | 3.13%   |
| Eindhoven            | 1         | 3.13%   |
| Córdoba             | 1         | 3.13%   |
| Belfast              | 1         | 3.13%   |
| Addlestone           | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 20%     |
| Seagate             | 4         | 4      | 11.43%  |
| WDC                 | 3         | 3      | 8.57%   |
| Transcend           | 3         | 3      | 8.57%   |
| SanDisk             | 3         | 3      | 8.57%   |
| Toshiba             | 2         | 2      | 5.71%   |
| Kingston            | 2         | 3      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| UMIS                | 1         | 1      | 2.86%   |
| SPCC                | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| Phison              | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| Hitachi             | 1         | 2      | 2.86%   |
| Corsair             | 1         | 1      | 2.86%   |
| AirDisk             | 1         | 1      | 2.86%   |
| A-DATA Technology   | 1         | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB       | 2         | 5.41%   |
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 2.7%    |
| WDC WD40EFAX-68JH4N0 4TB          | 1         | 2.7%    |
| WDC WD30EZRZ-00GXCB0 3TB          | 1         | 2.7%    |
| UMIS RPJTJ256MED1OWX 256GB        | 1         | 2.7%    |
| Transcend TS512GSSD230S 512GB     | 1         | 2.7%    |
| Transcend TS128GSSD340K 128GB     | 1         | 2.7%    |
| Transcend TS128GSSD340 128GB      | 1         | 2.7%    |
| Toshiba MK3265GSX 320GB           | 1         | 2.7%    |
| Toshiba KBG40ZNT512G MEMORY 512GB | 1         | 2.7%    |
| SPCC Solid State Disk 128GB       | 1         | 2.7%    |
| SK hynix HFM512GDHTNG-8710B 512GB | 1         | 2.7%    |
| Seagate ST9250315AS 250GB         | 1         | 2.7%    |
| Seagate ST9160314AS 160GB         | 1         | 2.7%    |
| Seagate ST310212A 10GB            | 1         | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 2.7%    |
| SanDisk X400 M.2 2280 256GB       | 1         | 2.7%    |
| SanDisk SDSSDA240G 240GB          | 1         | 2.7%    |
| SanDisk pSSD 256GB                | 1         | 2.7%    |
| Samsung SSD PM851 2.5 7mm 256GB   | 1         | 2.7%    |
| Samsung SSD 970 EVO Plus 2TB      | 1         | 2.7%    |
| Samsung SSD 970 EVO Plus 1TB      | 1         | 2.7%    |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 2.7%    |
| Samsung SSD 850 EVO mSATA 1TB     | 1         | 2.7%    |
| Samsung SSD 850 EVO 2TB           | 1         | 2.7%    |
| Samsung PM981a NVMe 512GB         | 1         | 2.7%    |
| Samsung MZ7LN256HCHP-000L1 256GB  | 1         | 2.7%    |
| Phison Sabrent Rocket nano 512GB  | 1         | 2.7%    |
| Kingston SA400M8240G 240GB        | 1         | 2.7%    |
| Intel SSDPEKKF256G8L 256GB        | 1         | 2.7%    |
| Hitachi HTS545050B9A300 500GB     | 1         | 2.7%    |
| Crucial CT256MX100SSD1 256GB      | 1         | 2.7%    |
| Crucial CT2000BX500SSD1 2TB       | 1         | 2.7%    |
| Corsair MP600 GS 1TB              | 1         | 2.7%    |
| AirDisk 512GB SSD                 | 1         | 2.7%    |
| A-DATA SSD DP900 512GB-DL3        | 1         | 2.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| WDC     | 3         | 3      | 33.33%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 2      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 29.41%  |
| Transcend           | 3         | 3      | 17.65%  |
| SanDisk             | 3         | 3      | 17.65%  |
| Kingston            | 2         | 3      | 11.76%  |
| Crucial             | 2         | 2      | 11.76%  |
| SPCC                | 1         | 1      | 5.88%   |
| A-DATA Technology   | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 17        | 18     | 53.13%  |
| NVMe | 8         | 10     | 25%     |
| HDD  | 7         | 10     | 21.88%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 28     | 73.33%  |
| NVMe | 8         | 10     | 26.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 19     | 64%     |
| 0.51-1.0   | 5         | 5      | 20%     |
| 1.01-2.0   | 2         | 2      | 8%      |
| 3.01-4.0   | 1         | 1      | 4%      |
| 2.01-3.0   | 1         | 1      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 21        | 65.63%  |
| 21-50      | 4         | 12.5%   |
| 101-250    | 4         | 12.5%   |
| 251-500    | 1         | 3.13%   |
| 501-1000   | 1         | 3.13%   |
| 51-100     | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 32        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Toshiba MK3265GSX 320GB       | 1         | 1      | 25%     |
| Seagate ST9250315AS 250GB     | 1         | 1      | 25%     |
| Seagate ST310212A 10GB        | 1         | 1      | 25%     |
| Hitachi HTS545050B9A300 500GB | 1         | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| Toshiba | 1         | 1      | 25%     |
| Hitachi | 1         | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| Toshiba | 1         | 1      | 25%     |
| Hitachi | 1         | 2      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model              | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 26        | 32     | 83.87%  |
| Malfunc | 4         | 5      | 12.9%   |
| Failed  | 1         | 1      | 3.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 22        | 59.46%  |
| Nvidia                                  | 3         | 8.11%   |
| Samsung Electronics                     | 2         | 5.41%   |
| Phison Electronics                      | 2         | 5.41%   |
| AMD                                     | 2         | 5.41%   |
| SK hynix                                | 1         | 2.7%    |
| Shenzhen Unionmemory Information System | 1         | 2.7%    |
| Sandisk                                 | 1         | 2.7%    |
| MAXIO Technology (Hangzhou)             | 1         | 2.7%    |
| KIOXIA                                  | 1         | 2.7%    |
| ASMedia Technology                      | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 6.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 6.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 4.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 4.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 4.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 4.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 4.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 4.65%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 2.33%   |
| Shenzhen Unionmemory Information System AM611 PCIe 3.0 NVMe SSD 256GB                   | 1         | 2.33%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1         | 2.33%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                                     | 1         | 2.33%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 2.33%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                | 1         | 2.33%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 2.33%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 2.33%   |
| Nvidia MCP61 IDE                                                                        | 1         | 2.33%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1         | 2.33%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 1         | 2.33%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                        | 1         | 2.33%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 2.33%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1         | 2.33%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                                | 1         | 2.33%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                                | 1         | 2.33%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1         | 2.33%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 2.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1         | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 21        | 55.26%  |
| NVMe | 9         | 23.68%  |
| IDE  | 5         | 13.16%  |
| RAID | 2         | 5.26%   |
| SAS  | 1         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 87.5%   |
| AMD    | 4         | 12.5%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 2         | 6.25%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 3.13%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz           | 1         | 3.13%   |
| Intel CPU Version                             | 1         | 3.13%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 3.13%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 3.13%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 3.13%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 3.13%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 3.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.13%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 3.13%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 3.13%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 3.13%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 3.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 3.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.13%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 3.13%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 3.13%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 3.13%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 1         | 3.13%   |
| Intel 13th Gen Core i7-1355U                  | 1         | 3.13%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 3.13%   |
| Intel 11th Gen Core i5-1130G7 @ 1.10GHz       | 1         | 3.13%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1         | 3.13%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD Phenom II X4 945 Processor                | 1         | 3.13%   |
| AMD New Processor Technology                  | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 31.25%  |
| Intel Core i7           | 6         | 18.75%  |
| Other                   | 5         | 15.63%  |
| Intel Xeon              | 2         | 6.25%   |
| Intel Celeron Dual-Core | 2         | 6.25%   |
| Intel Atom              | 2         | 6.25%   |
| AMD Ryzen 7             | 2         | 6.25%   |
| Intel Core i3           | 1         | 3.13%   |
| Intel Core 2 Duo        | 1         | 3.13%   |
| AMD Phenom II X4        | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 13        | 40.63%  |
| 2       | 11        | 34.38%  |
| 12      | 2         | 6.25%   |
| Unknown | 2         | 6.25%   |
| 16      | 1         | 3.13%   |
| 8       | 1         | 3.13%   |
| 6       | 1         | 3.13%   |
| 1       | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 30        | 93.75%  |
| 2       | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 19        | 59.38%  |
| 1       | 11        | 34.38%  |
| Unknown | 2         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 25%     |
| IvyBridge   | 5         | 15.63%  |
| Haswell     | 5         | 15.63%  |
| Penryn      | 4         | 12.5%   |
| K10         | 2         | 6.25%   |
| Bonnell     | 2         | 6.25%   |
| Unknown     | 2         | 6.25%   |
| Zen+        | 1         | 3.13%   |
| Zen 3       | 1         | 3.13%   |
| TigerLake   | 1         | 3.13%   |
| SandyBridge | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 65.71%  |
| Nvidia | 8         | 22.86%  |
| AMD    | 4         | 11.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 8.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 5.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 5.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 5.71%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 2         | 5.71%   |
| Nvidia MCP89 [GeForce 320M]                                                 | 1         | 2.86%   |
| Nvidia GT216M [GeForce GT 240M]                                             | 1         | 2.86%   |
| Nvidia GP102 [TITAN X]                                                      | 1         | 2.86%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 2.86%   |
| Nvidia GF108GLM [Quadro 1000M]                                              | 1         | 2.86%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 2.86%   |
| Nvidia C79 [GeForce G102M]                                                  | 1         | 2.86%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1         | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 2.86%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1         | 2.86%   |
| Intel UHD Graphics 620                                                      | 1         | 2.86%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                                 | 1         | 2.86%   |
| Intel Raptor Lake-P [UHD Graphics]                                          | 1         | 2.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 2.86%   |
| Intel Iris Plus Graphics 640                                                | 1         | 2.86%   |
| Intel HD Graphics 620                                                       | 1         | 2.86%   |
| Intel HD Graphics 615                                                       | 1         | 2.86%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 1         | 2.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1         | 2.86%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                | 1         | 2.86%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 1         | 2.86%   |
| AMD Cape Verde GL [FirePro W4100]                                           | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 53.13%  |
| 1 x Nvidia     | 6         | 18.75%  |
| 1 x AMD        | 4         | 12.5%   |
| 2 x Intel      | 3         | 9.38%   |
| Intel + Nvidia | 2         | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 28        | 87.5%   |
| Proprietary | 3         | 9.38%   |
| Unknown     | 1         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 96.88%  |
| 3.01-4.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| ViewSonic           | 2         | 14.29%  |
| Samsung Electronics | 2         | 14.29%  |
| HannStar            | 2         | 14.29%  |
| Chimei Innolux      | 2         | 14.29%  |
| AU Optronics        | 2         | 14.29%  |
| NEC Computers       | 1         | 7.14%   |
| LG Display          | 1         | 7.14%   |
| BOE                 | 1         | 7.14%   |
| Apple               | 1         | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch           | 1         | 7.14%   |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch        | 1         | 7.14%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch | 1         | 7.14%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 7.14%   |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch         | 1         | 7.14%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch          | 1         | 7.14%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 7.14%   |
| HannStar HSD140PHW1 HSD0583 1366x768 310x170mm 13.9-inch             | 1         | 7.14%   |
| Chimei Innolux LCD Monitor CMN1301 2160x1350 280x170mm 12.9-inch     | 1         | 7.14%   |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 260x140mm 11.6-inch     | 1         | 7.14%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                | 1         | 7.14%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch       | 1         | 7.14%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 290x170mm 13.2-inch       | 1         | 7.14%   |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                | 1         | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 6         | 42.86%  |
| 1366x768 (WXGA) | 3         | 21.43%  |
| 3840x2160 (4K)  | 1         | 7.14%   |
| 2880x1800       | 1         | 7.14%   |
| 2560x1440 (QHD) | 1         | 7.14%   |
| 2160x1350       | 1         | 7.14%   |
| 1024x600        | 1         | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 4         | 28.57%  |
| 15     | 3         | 21.43%  |
| 12     | 2         | 14.29%  |
| 27     | 1         | 7.14%   |
| 24     | 1         | 7.14%   |
| 23     | 1         | 7.14%   |
| 11     | 1         | 7.14%   |
| 10     | 1         | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 6         | 42.86%  |
| 301-350     | 5         | 35.71%  |
| 501-600     | 3         | 21.43%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 12        | 85.71%  |
| 16/10 | 2         | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 3         | 21.43%  |
| 71-80          | 2         | 14.29%  |
| 201-250        | 2         | 14.29%  |
| 91-100         | 2         | 14.29%  |
| 61-70          | 1         | 7.14%   |
| 51-60          | 1         | 7.14%   |
| 41-50          | 1         | 7.14%   |
| 301-350        | 1         | 7.14%   |
| 101-110        | 1         | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 4         | 28.57%  |
| 121-160       | 3         | 21.43%  |
| 51-100        | 3         | 21.43%  |
| More than 240 | 2         | 14.29%  |
| 161-240       | 2         | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 25        | 78.13%  |
| 0     | 7         | 21.88%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 21        | 41.18%  |
| Realtek Semiconductor             | 9         | 17.65%  |
| Qualcomm Atheros                  | 6         | 11.76%  |
| Broadcom                          | 5         | 9.8%    |
| Samsung Electronics               | 3         | 5.88%   |
| TP-Link                           | 1         | 1.96%   |
| Sierra Wireless                   | 1         | 1.96%   |
| Ralink Technology                 | 1         | 1.96%   |
| Marvell Technology Group          | 1         | 1.96%   |
| Ericsson Business Mobile Networks | 1         | 1.96%   |
| D-Link                            | 1         | 1.96%   |
| Apple                             | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 6         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 5         | 7.94%   |
| Samsung Galaxy series, misc. (tethering mode)                               | 3         | 4.76%   |
| Intel Ethernet Connection I217-LM                                           | 3         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 3.17%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 3.17%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 3.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 3.17%   |
| TP-Link Wireless USB Adapter                                                | 1         | 1.59%   |
| Sierra Wireless EM7305 Modem                                                | 1         | 1.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 1         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 1.59%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                          | 1         | 1.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 1.59%   |
| Ralink RT5372 Wireless Adapter                                              | 1         | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 1.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 1.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 1         | 1.59%   |
| Intel Wireless 8260                                                         | 1         | 1.59%   |
| Intel Wireless 7260                                                         | 1         | 1.59%   |
| Intel WiFi Link 5100                                                        | 1         | 1.59%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.59%   |
| Intel Wi-Fi 6 AX200                                                         | 1         | 1.59%   |
| Intel Raptor Lake PCH CNVi WiFi                                             | 1         | 1.59%   |
| Intel I210 Gigabit Network Connection                                       | 1         | 1.59%   |
| Intel Ethernet Controller I225-V                                            | 1         | 1.59%   |
| Intel Ethernet Controller I219-V                                            | 1         | 1.59%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                                        | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 1.59%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.59%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]        | 1         | 1.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                           | 1         | 1.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 48.39%  |
| Qualcomm Atheros      | 6         | 19.35%  |
| Realtek Semiconductor | 4         | 12.9%   |
| Broadcom              | 3         | 9.68%   |
| TP-Link               | 1         | 3.23%   |
| Ralink Technology     | 1         | 3.23%   |
| D-Link                | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 6.45%   |
| Intel Wireless 8265 / 8275                                              | 2         | 6.45%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 6.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 6.45%   |
| TP-Link Wireless USB Adapter                                            | 1         | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 3.23%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                      | 1         | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 3.23%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 3.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 3.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 3.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.23%   |
| Intel Wireless 8260                                                     | 1         | 3.23%   |
| Intel Wireless 7260                                                     | 1         | 3.23%   |
| Intel WiFi Link 5100                                                    | 1         | 3.23%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 3.23%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 3.23%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 1         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 3.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 3.23%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]    | 1         | 3.23%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 3.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 3.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 13        | 44.83%  |
| Realtek Semiconductor    | 7         | 24.14%  |
| Samsung Electronics      | 3         | 10.34%  |
| Broadcom                 | 3         | 10.34%  |
| Qualcomm Atheros         | 1         | 3.45%   |
| Marvell Technology Group | 1         | 3.45%   |
| Apple                    | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 20%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 16.67%  |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 10%     |
| Intel Ethernet Connection I217-LM                                 | 3         | 10%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.33%   |
| Intel I210 Gigabit Network Connection                             | 1         | 3.33%   |
| Intel Ethernet Controller I225-V                                  | 1         | 3.33%   |
| Intel Ethernet Controller I219-V                                  | 1         | 3.33%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 3.33%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 3.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.33%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 48.21%  |
| Ethernet | 27        | 48.21%  |
| Unknown  | 2         | 3.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 15        | 55.56%  |
| WiFi     | 12        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 18        | 56.25%  |
| 1     | 12        | 37.5%   |
| 3     | 1         | 3.13%   |
| 0     | 1         | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 90.63%  |
| Yes  | 3         | 9.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 55.56%  |
| Broadcom                        | 3         | 16.67%  |
| Realtek Semiconductor           | 2         | 11.11%  |
| Qualcomm Atheros Communications | 1         | 5.56%   |
| Cambridge Silicon Radio         | 1         | 5.56%   |
| Apple                           | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 22.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 11.11%  |
| Intel AX201 Bluetooth                               | 2         | 11.11%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 5.56%   |
| Realtek RTL8723B Bluetooth                          | 1         | 5.56%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)     | 1         | 5.56%   |
| Intel Wireless Bluetooth                            | 1         | 5.56%   |
| Intel AX200 Bluetooth                               | 1         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.56%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 5.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 5.56%   |
| Apple Bluetooth Host Controller                     | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 27        | 69.23%  |
| Nvidia                  | 6         | 15.38%  |
| AMD                     | 4         | 10.26%  |
| Creative Labs           | 1         | 2.56%   |
| BEHRINGER International | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 6.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 6.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 4.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 4.17%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 4.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.17%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 4.17%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.08%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 2.08%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 2.08%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.08%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 2.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.08%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 2.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 2.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 2.08%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 2.08%   |
| BEHRINGER International UMC 202HD 192k                                     | 1         | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 2.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 2.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 28.95%  |
| SK hynix            | 7         | 18.42%  |
| Kingston            | 5         | 13.16%  |
| Micron Technology   | 4         | 10.53%  |
| Unknown             | 4         | 10.53%  |
| Unknown             | 1         | 2.63%   |
| Transcend           | 1         | 2.63%   |
| Ramaxel Technology  | 1         | 2.63%   |
| Nanya Technology    | 1         | 2.63%   |
| Corsair             | 1         | 2.63%   |
| A-DATA Technology   | 1         | 2.63%   |
| 48spaces            | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 4         | 9.52%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 4.76%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 2.38%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s                         | 1         | 2.38%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s                         | 1         | 2.38%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 1         | 2.38%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.38%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 2.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 2.38%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 2.38%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 2.38%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.38%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 2.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 2.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.38%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 2.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.38%   |
| Samsung RAM M425R1GB4DB0-CWMOL 16GB SODIMM DDR5 5600MT/s                  | 1         | 2.38%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM SDRAM 1639MT/s                   | 1         | 2.38%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s                       | 1         | 2.38%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 2.38%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 2.38%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.38%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 667MT/s                       | 1         | 2.38%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                              | 1         | 2.38%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s                        | 1         | 2.38%   |
| Micron RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                        | 1         | 2.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 2.38%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s                       | 1         | 2.38%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2400MT/s                   | 1         | 2.38%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.38%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s                     | 1         | 2.38%   |
| Kingston RAM 9905428-105.A00G 8GB SODIMM DDR3 1333MT/s                    | 1         | 2.38%   |
| Corsair RAM CMY16GX3M2A2133C11 8GB DIMM DDR3 1866MT/s                     | 1         | 2.38%   |
| A-DATA RAM MIOVE1B163BZ 2GB SODIMM SDRAM 1639MT/s                         | 1         | 2.38%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 14        | 42.42%  |
| DDR4   | 8         | 24.24%  |
| DDR2   | 4         | 12.12%  |
| LPDDR3 | 3         | 9.09%   |
| SDRAM  | 1         | 3.03%   |
| LPDDR5 | 1         | 3.03%   |
| LPDDR4 | 1         | 3.03%   |
| DDR5   | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 68.75%  |
| DIMM         | 6         | 18.75%  |
| Row Of Chips | 4         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 15        | 39.47%  |
| 4096  | 11        | 28.95%  |
| 2048  | 9         | 23.68%  |
| 16384 | 3         | 7.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 8         | 23.53%  |
| 2667  | 5         | 14.71%  |
| 667   | 3         | 8.82%   |
| 2400  | 2         | 5.88%   |
| 2133  | 2         | 5.88%   |
| 1333  | 2         | 5.88%   |
| 1067  | 2         | 5.88%   |
| 6400  | 1         | 2.94%   |
| 5600  | 1         | 2.94%   |
| 4267  | 1         | 2.94%   |
| 3600  | 1         | 2.94%   |
| 1867  | 1         | 2.94%   |
| 1866  | 1         | 2.94%   |
| 1639  | 1         | 2.94%   |
| 1334  | 1         | 2.94%   |
| 533   | 1         | 2.94%   |
| 400   | 1         | 2.94%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 5         | 26.32%  |
| IMC Networks                  | 3         | 15.79%  |
| Bison Electronics             | 3         | 15.79%  |
| Suyin                         | 2         | 10.53%  |
| Realtek Semiconductor         | 2         | 10.53%  |
| Z-Star Microelectronics       | 1         | 5.26%   |
| Sunplus Innovation Technology | 1         | 5.26%   |
| Microdia                      | 1         | 5.26%   |
| Luxvisions Innotech Limited   | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison SunplusIT Integrated Camera                           | 2         | 10.53%  |
| Z-Star Webcam                                               | 1         | 5.26%   |
| Suyin HD Video WebCam                                       | 1         | 5.26%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 5.26%   |
| Sunplus Hy HD Camera                                        | 1         | 5.26%   |
| Realtek Lenovo EasyCamera                                   | 1         | 5.26%   |
| Realtek Integrated_Webcam_HD                                | 1         | 5.26%   |
| Microdia Integrated Webcam                                  | 1         | 5.26%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 5.26%   |
| IMC Networks UVC VGA Webcam                                 | 1         | 5.26%   |
| IMC Networks Integrated Camera                              | 1         | 5.26%   |
| IMC Networks EasyCamera                                     | 1         | 5.26%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 1         | 5.26%   |
| Chicony Integrated Camera                                   | 1         | 5.26%   |
| Chicony HD WebCam                                           | 1         | 5.26%   |
| Chicony FJ Camera                                           | 1         | 5.26%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 5.26%   |
| Bison ThinkPad Integrated Camera                            | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Upek                       | 2         | 28.57%  |
| LighTuning Technology      | 2         | 28.57%  |
| Validity Sensors           | 1         | 14.29%  |
| Synaptics                  | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 28.57%  |
| Validity Sensors Synaptics WBDI                        | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 14.29%  |
| LighTuning Fingerprint Reader                          | 1         | 14.29%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 14.29%  |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 10        | 31.25%  |
| 2     | 9         | 28.13%  |
| 0     | 6         | 18.75%  |
| 4     | 3         | 9.38%   |
| 3     | 3         | 9.38%   |
| 7     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 22        | 41.51%  |
| Bluetooth                | 9         | 16.98%  |
| Net/wireless             | 8         | 15.09%  |
| Fingerprint reader       | 6         | 11.32%  |
| Firewire controller      | 4         | 7.55%   |
| Card reader              | 2         | 3.77%   |
| Sound                    | 1         | 1.89%   |
| Net/ethernet             | 1         | 1.89%   |

