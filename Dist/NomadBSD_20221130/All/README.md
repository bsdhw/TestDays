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

Total: 29

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 24        | 96%     |
| i386  | 1         | 4%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 15        | 60%     |
| xinitrc       | 6         | 24%     |
| KDE5          | 2         | 8%      |
| Enlightenment | 2         | 8%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 25        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 23        | 92%     |
| LightDM | 2         | 8%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 8         | 32%     |
| en_GB   | 5         | 20%     |
| fr_FR   | 4         | 16%     |
| Unknown | 3         | 12%     |
| fi_FI   | 2         | 8%      |
| ru_RU   | 1         | 4%      |
| lt_LT   | 1         | 4%      |
| bg_BG   | 1         | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 25        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 16        | 64%     |
| Zfs  | 9         | 36%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 15        | 60%     |
| MBR  | 10        | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 11        | 44%     |
| Hewlett-Packard     | 2         | 8%      |
| Acer                | 2         | 8%      |
| Samsung Electronics | 1         | 4%      |
| Fujitsu Siemens     | 1         | 4%      |
| Fujitsu             | 1         | 4%      |
| ECS                 | 1         | 4%      |
| Dell                | 1         | 4%      |
| Chuwi               | 1         | 4%      |
| ASUSTek Computer    | 1         | 4%      |
| ASRockRack          | 1         | 4%      |
| ASRock              | 1         | 4%      |
| Apple               | 1         | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung N150/N210/N220                   | 1         | 4%      |
| Lenovo Yoga 710-11IKB 80V6               | 1         | 4%      |
| Lenovo ThinkPad X280 20KESB4T00          | 1         | 4%      |
| Lenovo ThinkPad X230 2325IB1             | 1         | 4%      |
| Lenovo ThinkPad X230 23255NG             | 1         | 4%      |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT | 1         | 4%      |
| Lenovo ThinkPad W520 42844DG             | 1         | 4%      |
| Lenovo ThinkPad T470 20HES0EV0A          | 1         | 4%      |
| Lenovo ThinkPad E495 20NE000BSP          | 1         | 4%      |
| Lenovo ThinkPad E14 20RA0036RT           | 1         | 4%      |
| Lenovo ThinkCentre M93p 10AAS4EN00       | 1         | 4%      |
| Lenovo G50-70 20351                      | 1         | 4%      |
| HP Z420 Workstation                      | 1         | 4%      |
| HP EliteBook 750 G1                      | 1         | 4%      |
| Fujitsu Siemens AMILO Li3710             | 1         | 4%      |
| Fujitsu CELSIUS H730                     | 1         | 4%      |
| ECS Z77H2-AX                             | 1         | 4%      |
| Dell Latitude 7300                       | 1         | 4%      |
| Chuwi CoreBook X                         | 1         | 4%      |
| ASUS ROG STRIX B550-F GAMING             | 1         | 4%      |
| ASRockRack C226M WS                      | 1         | 4%      |
| ASRock N68-S UCC                         | 1         | 4%      |
| Apple MacBookPro14,1                     | 1         | 4%      |
| Acer Swift SF314-56                      | 1         | 4%      |
| Acer Aspire 7738                         | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 8         | 32%     |
| Samsung N150          | 1         | 4%      |
| Lenovo Yoga           | 1         | 4%      |
| Lenovo ThinkCentre    | 1         | 4%      |
| Lenovo G50-70         | 1         | 4%      |
| HP Z420               | 1         | 4%      |
| HP EliteBook          | 1         | 4%      |
| Fujitsu Siemens AMILO | 1         | 4%      |
| Fujitsu CELSIUS       | 1         | 4%      |
| ECS Z77H2-AX          | 1         | 4%      |
| Dell Latitude         | 1         | 4%      |
| Chuwi CoreBook        | 1         | 4%      |
| ASUS ROG              | 1         | 4%      |
| ASRockRack C226M      | 1         | 4%      |
| ASRock N68-S          | 1         | 4%      |
| Apple MacBookPro14    | 1         | 4%      |
| Acer Swift            | 1         | 4%      |
| Acer Aspire           | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 4         | 16%     |
| 2020 | 3         | 12%     |
| 2019 | 3         | 12%     |
| 2022 | 2         | 8%      |
| 2018 | 2         | 8%      |
| 2015 | 2         | 8%      |
| 2009 | 2         | 8%      |
| 2023 | 1         | 4%      |
| 2021 | 1         | 4%      |
| 2016 | 1         | 4%      |
| 2014 | 1         | 4%      |
| 2013 | 1         | 4%      |
| 2011 | 1         | 4%      |
| 2010 | 1         | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 19        | 76%     |
| Desktop  | 6         | 24%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 24        | 96%     |
| Yes  | 1         | 4%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 11        | 44%     |
| 16.01-24.0 | 7         | 28%     |
| 32.01-64.0 | 3         | 12%     |
| 2.01-3.0   | 2         | 8%      |
| 4.01-8.0   | 1         | 4%      |
| 24.01-32.0 | 1         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 11        | 44%     |
| 0.51-1.0 | 9         | 36%     |
| 1.01-2.0 | 4         | 16%     |
| 2.01-3.0 | 1         | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 17        | 68%     |
| 2      | 4         | 16%     |
| 0      | 2         | 8%      |
| 4      | 1         | 4%      |
| 3      | 1         | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 21        | 84%     |
| Yes       | 4         | 16%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 76%     |
| No        | 6         | 24%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 80%     |
| No        | 5         | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 60%     |
| No        | 10        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| France      | 6         | 24%     |
| UK          | 5         | 20%     |
| USA         | 4         | 16%     |
| Russia      | 2         | 8%      |
| Finland     | 2         | 8%      |
| Spain       | 1         | 4%      |
| San Marino  | 1         | 4%      |
| Netherlands | 1         | 4%      |
| Lithuania   | 1         | 4%      |
| Bulgaria    | 1         | 4%      |
| Argentina   | 1         | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Urcuit               | 2         | 8%      |
| Moscow               | 2         | 8%      |
| Melun                | 2         | 8%      |
| Lutherville-Timonium | 2         | 8%      |
| West Bromwich        | 1         | 4%      |
| Wakefield            | 1         | 4%      |
| Vilnius              | 1         | 4%      |
| Vaasa                | 1         | 4%      |
| Turku                | 1         | 4%      |
| Sofia                | 1         | 4%      |
| Seattle              | 1         | 4%      |
| Sartrouville         | 1         | 4%      |
| San Marino           | 1         | 4%      |
| Saint-Raphaël       | 1         | 4%      |
| Rubí                | 1         | 4%      |
| Portland             | 1         | 4%      |
| Lincoln              | 1         | 4%      |
| Eindhoven            | 1         | 4%      |
| Córdoba             | 1         | 4%      |
| Belfast              | 1         | 4%      |
| Addlestone           | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 20%     |
| Seagate             | 4         | 4      | 13.33%  |
| WDC                 | 3         | 3      | 10%     |
| SanDisk             | 3         | 3      | 10%     |
| Kingston            | 2         | 3      | 6.67%   |
| Crucial             | 2         | 2      | 6.67%   |
| UMIS                | 1         | 1      | 3.33%   |
| Toshiba             | 1         | 1      | 3.33%   |
| SPCC                | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| Phison              | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| Hitachi             | 1         | 2      | 3.33%   |
| Corsair             | 1         | 1      | 3.33%   |
| AirDisk             | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB       | 2         | 6.25%   |
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 3.13%   |
| WDC WD40EFAX-68JH4N0 4TB          | 1         | 3.13%   |
| WDC WD30EZRZ-00GXCB0 3TB          | 1         | 3.13%   |
| UMIS RPJTJ256MED1OWX 256GB        | 1         | 3.13%   |
| Toshiba KBG40ZNT512G MEMORY 512GB | 1         | 3.13%   |
| SPCC Solid State Disk 128GB       | 1         | 3.13%   |
| SK hynix HFM512GDHTNG-8710B 512GB | 1         | 3.13%   |
| Seagate ST9250315AS 250GB         | 1         | 3.13%   |
| Seagate ST9160314AS 160GB         | 1         | 3.13%   |
| Seagate ST310212A 10GB            | 1         | 3.13%   |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 3.13%   |
| SanDisk X400 M.2 2280 256GB       | 1         | 3.13%   |
| SanDisk SDSSDA240G 240GB          | 1         | 3.13%   |
| SanDisk pSSD 256GB                | 1         | 3.13%   |
| Samsung SSD PM851 2.5 7mm 256GB   | 1         | 3.13%   |
| Samsung SSD 970 EVO Plus 2TB      | 1         | 3.13%   |
| Samsung SSD 970 EVO Plus 1TB      | 1         | 3.13%   |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 3.13%   |
| Samsung SSD 850 EVO mSATA 1TB     | 1         | 3.13%   |
| Samsung SSD 850 EVO 2TB           | 1         | 3.13%   |
| Samsung MZ7LN256HCHP-000L1 256GB  | 1         | 3.13%   |
| Phison Sabrent Rocket nano 512GB  | 1         | 3.13%   |
| Kingston SA400M8240G 240GB        | 1         | 3.13%   |
| Intel SSDPEKKF256G8L 256GB        | 1         | 3.13%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 3.13%   |
| Crucial CT256MX100SSD1 256GB      | 1         | 3.13%   |
| Crucial CT2000BX500SSD1 2TB       | 1         | 3.13%   |
| Corsair MP600 GS 1TB              | 1         | 3.13%   |
| AirDisk 512GB SSD                 | 1         | 3.13%   |
| A-DATA SSD DP900 512GB-DL3        | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| WDC     | 3         | 3      | 37.5%   |
| Hitachi | 1         | 2      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 35.71%  |
| SanDisk             | 3         | 3      | 21.43%  |
| Kingston            | 2         | 3      | 14.29%  |
| Crucial             | 2         | 2      | 14.29%  |
| SPCC                | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 14        | 15     | 51.85%  |
| NVMe | 7         | 9      | 25.93%  |
| HDD  | 6         | 9      | 22.22%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 24     | 72%     |
| NVMe | 7         | 9      | 28%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 16     | 61.9%   |
| 0.51-1.0   | 4         | 4      | 19.05%  |
| 1.01-2.0   | 2         | 2      | 9.52%   |
| 3.01-4.0   | 1         | 1      | 4.76%   |
| 2.01-3.0   | 1         | 1      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 15        | 60%     |
| 101-250    | 4         | 16%     |
| 21-50      | 3         | 12%     |
| 251-500    | 1         | 4%      |
| 501-1000   | 1         | 4%      |
| 51-100     | 1         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 25        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB     | 1         | 1      | 33.33%  |
| Seagate ST310212A 10GB        | 1         | 1      | 33.33%  |
| Hitachi HTS545050B9A300 500GB | 1         | 2      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model              | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 22        | 28     | 84.62%  |
| Malfunc | 3         | 4      | 11.54%  |
| Failed  | 1         | 1      | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 20        | 66.67%  |
| Phison Electronics                      | 2         | 6.67%   |
| SK hynix                                | 1         | 3.33%   |
| Shenzhen Unionmemory Information System | 1         | 3.33%   |
| Samsung Electronics                     | 1         | 3.33%   |
| Nvidia                                  | 1         | 3.33%   |
| MAXIO Technology (Hangzhou)             | 1         | 3.33%   |
| KIOXIA                                  | 1         | 3.33%   |
| ASMedia Technology                      | 1         | 3.33%   |
| AMD                                     | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 8.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 8.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 5.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 5.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 5.88%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 2.94%   |
| Shenzhen Unionmemory Information System AM611 PCIe 3.0 NVMe SSD 256GB          | 1         | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.94%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1         | 2.94%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.94%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 2.94%   |
| Nvidia MCP61 IDE                                                               | 1         | 2.94%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 2.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 2.94%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 2.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.94%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1         | 2.94%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1         | 2.94%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                       | 1         | 2.94%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 2.94%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.94%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 2.94%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 2.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 17        | 56.67%  |
| NVMe | 7         | 23.33%  |
| IDE  | 3         | 10%     |
| RAID | 2         | 6.67%   |
| SAS  | 1         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 88%     |
| AMD    | 3         | 12%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 4%      |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz           | 1         | 4%      |
| Intel CPU Version                             | 1         | 4%      |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 4%      |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 4%      |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 4%      |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 4%      |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 4%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 4%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4%      |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 4%      |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 4%      |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 4%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 4%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4%      |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 4%      |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 4%      |
| Intel Atom CPU N450 @ 1.66GHz                 | 1         | 4%      |
| Intel 12th Gen Core i5-1235U                  | 1         | 4%      |
| Intel 11th Gen Core i5-1130G7 @ 1.10GHz       | 1         | 4%      |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1         | 4%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 4%      |
| AMD Phenom II X4 945 Processor                | 1         | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 9         | 36%     |
| Intel Core i7           | 5         | 20%     |
| Other                   | 3         | 12%     |
| Intel Xeon              | 2         | 8%      |
| AMD Ryzen 7             | 2         | 8%      |
| Intel Core i3           | 1         | 4%      |
| Intel Celeron Dual-Core | 1         | 4%      |
| Intel Atom              | 1         | 4%      |
| AMD Phenom II X4        | 1         | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 11        | 44%     |
| 2       | 9         | 36%     |
| 16      | 1         | 4%      |
| 12      | 1         | 4%      |
| 8       | 1         | 4%      |
| 6       | 1         | 4%      |
| Unknown | 1         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 24        | 96%     |
| Unknown | 1         | 4%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 17        | 68%     |
| 1       | 7         | 28%     |
| Unknown | 1         | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 28%     |
| Haswell     | 5         | 20%     |
| IvyBridge   | 4         | 16%     |
| Penryn      | 2         | 8%      |
| Zen+        | 1         | 4%      |
| Zen 3       | 1         | 4%      |
| TigerLake   | 1         | 4%      |
| SandyBridge | 1         | 4%      |
| K10         | 1         | 4%      |
| Bonnell     | 1         | 4%      |
| Unknown     | 1         | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 71.43%  |
| Nvidia | 5         | 17.86%  |
| AMD    | 3         | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 10.71%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 7.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 7.14%   |
| Nvidia GT216M [GeForce GT 240M]                                             | 1         | 3.57%   |
| Nvidia GP102 [TITAN X]                                                      | 1         | 3.57%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 3.57%   |
| Nvidia GF108GLM [Quadro 1000M]                                              | 1         | 3.57%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 3.57%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1         | 3.57%   |
| Intel UHD Graphics 620                                                      | 1         | 3.57%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                                 | 1         | 3.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 3.57%   |
| Intel Iris Plus Graphics 640                                                | 1         | 3.57%   |
| Intel HD Graphics 620                                                       | 1         | 3.57%   |
| Intel HD Graphics 615                                                       | 1         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 3.57%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1         | 3.57%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 1         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1         | 3.57%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 1         | 3.57%   |
| AMD Cape Verde GL [FirePro W4100]                                           | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 60%     |
| 1 x Nvidia     | 3         | 12%     |
| 1 x AMD        | 3         | 12%     |
| 2 x Intel      | 2         | 8%      |
| Intel + Nvidia | 2         | 8%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 23        | 92%     |
| Proprietary | 2         | 8%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 20%     |
| Chimei Innolux      | 2         | 20%     |
| ViewSonic           | 1         | 10%     |
| NEC Computers       | 1         | 10%     |
| LG Display          | 1         | 10%     |
| BOE                 | 1         | 10%     |
| AU Optronics        | 1         | 10%     |
| Apple               | 1         | 10%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch        | 1         | 10%     |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch | 1         | 10%     |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 10%     |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch         | 1         | 10%     |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch          | 1         | 10%     |
| Chimei Innolux LCD Monitor CMN1301 2160x1350 280x170mm 12.9-inch     | 1         | 10%     |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 260x140mm 11.6-inch     | 1         | 10%     |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                | 1         | 10%     |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch       | 1         | 10%     |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                | 1         | 10%     |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 5         | 50%     |
| 1366x768 (WXGA) | 2         | 20%     |
| 2880x1800       | 1         | 10%     |
| 2560x1440 (QHD) | 1         | 10%     |
| 2160x1350       | 1         | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 3         | 30%     |
| 13     | 2         | 20%     |
| 12     | 2         | 20%     |
| 27     | 1         | 10%     |
| 23     | 1         | 10%     |
| 11     | 1         | 10%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 4         | 40%     |
| 201-300     | 4         | 40%     |
| 501-600     | 2         | 20%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 8         | 80%     |
| 16/10 | 2         | 20%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 2         | 20%     |
| 91-100         | 2         | 20%     |
| 71-80          | 1         | 10%     |
| 61-70          | 1         | 10%     |
| 51-60          | 1         | 10%     |
| 301-350        | 1         | 10%     |
| 201-250        | 1         | 10%     |
| 101-110        | 1         | 10%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 3         | 30%     |
| 161-240       | 2         | 20%     |
| 101-120       | 2         | 20%     |
| 51-100        | 2         | 20%     |
| More than 240 | 1         | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 20        | 80%     |
| 0     | 5         | 20%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 19        | 51.35%  |
| Realtek Semiconductor             | 7         | 18.92%  |
| Qualcomm Atheros                  | 3         | 8.11%   |
| Broadcom                          | 3         | 8.11%   |
| TP-Link                           | 1         | 2.7%    |
| Sierra Wireless                   | 1         | 2.7%    |
| Marvell Technology Group          | 1         | 2.7%    |
| Ericsson Business Mobile Networks | 1         | 2.7%    |
| Apple                             | 1         | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 5         | 10.87%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 4         | 8.7%    |
| Intel Ethernet Connection I217-LM                                           | 3         | 6.52%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 4.35%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 4.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 4.35%   |
| TP-Link Wireless USB Adapter                                                | 1         | 2.17%   |
| Sierra Wireless EM7305 Modem                                                | 1         | 2.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 1         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 2.17%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                          | 1         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 2.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 2.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 2.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 2.17%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 1         | 2.17%   |
| Intel Wireless 8260                                                         | 1         | 2.17%   |
| Intel Wireless 7260                                                         | 1         | 2.17%   |
| Intel WiFi Link 5100                                                        | 1         | 2.17%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 2.17%   |
| Intel I210 Gigabit Network Connection                                       | 1         | 2.17%   |
| Intel Ethernet Controller I225-V                                            | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-V                                        | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.17%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 2.17%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                             | 1         | 2.17%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                          | 1         | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.17%   |
| Apple Ethernet Adapter [A1277]                                              | 1         | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 56.52%  |
| Realtek Semiconductor | 4         | 17.39%  |
| Qualcomm Atheros      | 3         | 13.04%  |
| Broadcom              | 2         | 8.7%    |
| TP-Link               | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 2         | 8.7%    |
| Intel Centrino Ultimate-N 6300                                          | 2         | 8.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 8.7%    |
| TP-Link Wireless USB Adapter                                            | 1         | 4.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 4.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 4.35%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                      | 1         | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 4.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 4.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 4.35%   |
| Intel Wireless 8260                                                     | 1         | 4.35%   |
| Intel Wireless 7260                                                     | 1         | 4.35%   |
| Intel WiFi Link 5100                                                    | 1         | 4.35%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 4.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 4.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 4.35%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 4.35%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 12        | 60%     |
| Realtek Semiconductor    | 5         | 25%     |
| Marvell Technology Group | 1         | 5%      |
| Broadcom                 | 1         | 5%      |
| Apple                    | 1         | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 23.81%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 19.05%  |
| Intel Ethernet Connection I217-LM                                 | 3         | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 4.76%   |
| Intel I210 Gigabit Network Connection                             | 1         | 4.76%   |
| Intel Ethernet Controller I225-V                                  | 1         | 4.76%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.76%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 4.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.76%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 4.76%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 48.84%  |
| Ethernet | 20        | 46.51%  |
| Unknown  | 2         | 4.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 14        | 60.87%  |
| WiFi     | 9         | 39.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 13        | 52%     |
| 1     | 10        | 40%     |
| 3     | 1         | 4%      |
| 0     | 1         | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 23        | 92%     |
| Yes  | 2         | 8%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 53.33%  |
| Broadcom                        | 3         | 20%     |
| Realtek Semiconductor           | 2         | 13.33%  |
| Qualcomm Atheros Communications | 1         | 6.67%   |
| Cambridge Silicon Radio         | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 26.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 13.33%  |
| Intel AX201 Bluetooth                               | 2         | 13.33%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 6.67%   |
| Realtek RTL8723B Bluetooth                          | 1         | 6.67%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)     | 1         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.67%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 6.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 6.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 23        | 74.19%  |
| Nvidia                  | 3         | 9.68%   |
| AMD                     | 3         | 9.68%   |
| Creative Labs           | 1         | 3.23%   |
| BEHRINGER International | 1         | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 10.26%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 10.26%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 7.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 5.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 5.13%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 5.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 5.13%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 2.56%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.56%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 2.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.56%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 2.56%   |
| BEHRINGER International UMC 202HD 192k                                     | 1         | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 2.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 27.59%  |
| SK hynix            | 6         | 20.69%  |
| Kingston            | 5         | 17.24%  |
| Micron Technology   | 4         | 13.79%  |
| Unknown             | 3         | 10.34%  |
| Ramaxel Technology  | 1         | 3.45%   |
| Corsair             | 1         | 3.45%   |
| 48spaces            | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 3         | 9.38%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 6.25%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 3.13%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.13%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 3.13%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 3.13%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 3.13%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 3.13%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 3.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 3.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.13%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 3.13%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 3.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 3.13%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s                       | 1         | 3.13%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 3.13%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.13%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                              | 1         | 3.13%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s                        | 1         | 3.13%   |
| Micron RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                        | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 3.13%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s                       | 1         | 3.13%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2400MT/s                   | 1         | 3.13%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                   | 1         | 3.13%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s                     | 1         | 3.13%   |
| Kingston RAM 9905428-105.A00G 8GB SODIMM DDR3 1333MT/s                    | 1         | 3.13%   |
| Corsair RAM CMY16GX3M2A2133C11 8GB DIMM DDR3 1866MT/s                     | 1         | 3.13%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 11        | 42.31%  |
| DDR4   | 8         | 30.77%  |
| DDR2   | 3         | 11.54%  |
| LPDDR3 | 2         | 7.69%   |
| LPDDR5 | 1         | 3.85%   |
| LPDDR4 | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 68%     |
| DIMM         | 5         | 20%     |
| Row Of Chips | 3         | 12%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 41.38%  |
| 4096  | 10        | 34.48%  |
| 2048  | 5         | 17.24%  |
| 16384 | 2         | 6.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 8         | 29.63%  |
| 2667  | 5         | 18.52%  |
| 2400  | 2         | 7.41%   |
| 6400  | 1         | 3.7%    |
| 4267  | 1         | 3.7%    |
| 3600  | 1         | 3.7%    |
| 2133  | 1         | 3.7%    |
| 1867  | 1         | 3.7%    |
| 1866  | 1         | 3.7%    |
| 1334  | 1         | 3.7%    |
| 1333  | 1         | 3.7%    |
| 1067  | 1         | 3.7%    |
| 667   | 1         | 3.7%    |
| 533   | 1         | 3.7%    |
| 400   | 1         | 3.7%    |

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
| Chicony Electronics           | 4         | 28.57%  |
| Bison Electronics             | 3         | 21.43%  |
| Realtek Semiconductor         | 2         | 14.29%  |
| IMC Networks                  | 2         | 14.29%  |
| Z-Star Microelectronics       | 1         | 7.14%   |
| Suyin                         | 1         | 7.14%   |
| Sunplus Innovation Technology | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Bison SunplusIT Integrated Camera        | 2         | 14.29%  |
| Z-Star Webcam                            | 1         | 7.14%   |
| Suyin HD Video WebCam                    | 1         | 7.14%   |
| Sunplus Hy HD Camera                     | 1         | 7.14%   |
| Realtek Lenovo EasyCamera                | 1         | 7.14%   |
| Realtek Integrated_Webcam_HD             | 1         | 7.14%   |
| IMC Networks Integrated Camera           | 1         | 7.14%   |
| IMC Networks EasyCamera                  | 1         | 7.14%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 7.14%   |
| Chicony Integrated Camera                | 1         | 7.14%   |
| Chicony HD WebCam                        | 1         | 7.14%   |
| Chicony FJ Camera                        | 1         | 7.14%   |
| Bison ThinkPad Integrated Camera         | 1         | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Upek                  | 2         | 33.33%  |
| LighTuning Technology | 2         | 33.33%  |
| Validity Sensors      | 1         | 16.67%  |
| Synaptics             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 33.33%  |
| Validity Sensors Synaptics WBDI                        | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 16.67%  |
| LighTuning Fingerprint Reader                          | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 16.67%  |

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
| 2     | 9         | 36%     |
| 1     | 7         | 28%     |
| 3     | 3         | 12%     |
| 0     | 3         | 12%     |
| 4     | 2         | 8%      |
| 7     | 1         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 19        | 42.22%  |
| Bluetooth                | 8         | 17.78%  |
| Net/wireless             | 6         | 13.33%  |
| Fingerprint reader       | 6         | 13.33%  |
| Firewire controller      | 3         | 6.67%   |
| Card reader              | 2         | 4.44%   |
| Sound                    | 1         | 2.22%   |

