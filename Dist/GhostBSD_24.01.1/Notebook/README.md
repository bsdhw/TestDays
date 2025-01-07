GhostBSD 24.01.1 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for GhostBSD 24.01.1.

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

Total: 30

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | EliteBook 840 G6            | [9ae98f134a](https://bsd-hardware.info/?probe=9ae98f134a) | Aug 09, 2024 |
| Dell          | Inspiron 1545               | [e123332fb8](https://bsd-hardware.info/?probe=e123332fb8) | May 16, 2024 |
| Dell          | Inspiron 1545               | [d5f43a27aa](https://bsd-hardware.info/?probe=d5f43a27aa) | May 12, 2024 |
| Dell          | Inspiron 1545               | [3c3432b2c0](https://bsd-hardware.info/?probe=3c3432b2c0) | May 11, 2024 |
| Infinix       | INBook X1                   | [847a9cb112](https://bsd-hardware.info/?probe=847a9cb112) | May 10, 2024 |
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
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| Dell          | Latitude E5540              | [108e2acb98](https://bsd-hardware.info/?probe=108e2acb98) | Apr 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [db1d3cd098](https://bsd-hardware.info/?probe=db1d3cd098) | Mar 19, 2024 |
| Google        | Cave                        | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| Dell          | XPS 13 9305                 | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| Dell          | Inspiron 5559               | [ac72a9a34a](https://bsd-hardware.info/?probe=ac72a9a34a) | Feb 23, 2024 |
| Dell          | Latitude E6540              | [92ba9b26e1](https://bsd-hardware.info/?probe=92ba9b26e1) | Feb 21, 2024 |
| TUXEDO        | Aura 15 Gen1                | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 24        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MATE | 19        | 79.17%  |
| XFCE | 3         | 12.5%   |
| KDE5 | 1         | 4.17%   |
| dwm  | 1         | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 24        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 23        | 95.83%  |
| SDDM    | 1         | 4.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 13        | 54.17%  |
| C     | 5         | 20.83%  |
| es_ES | 2         | 8.33%   |
| de_DE | 2         | 8.33%   |
| ru_RU | 1         | 4.17%   |
| fr_FR | 1         | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 21        | 87.5%   |
| BIOS | 3         | 12.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 24        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 24        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 9         | 37.5%   |
| Lenovo           | 4         | 16.67%  |
| Hewlett-Packard  | 4         | 16.67%  |
| TUXEDO           | 1         | 4.17%   |
| Infinix          | 1         | 4.17%   |
| Google           | 1         | 4.17%   |
| F-Plus Mobile    | 1         | 4.17%   |
| ASUSTek Computer | 1         | 4.17%   |
| Alienware        | 1         | 4.17%   |
| Unknown          | 1         | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell XPS 13 9360                     | 2         | 8.33%   |
| TUXEDO Aura 15 Gen1                  | 1         | 4.17%   |
| Lenovo ThinkPad X240 20AMS3FY00      | 1         | 4.17%   |
| Lenovo ThinkPad X220 429135G         | 1         | 4.17%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW | 1         | 4.17%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 1         | 4.17%   |
| Infinix INBook X1                    | 1         | 4.17%   |
| HP ProBook 645 G3                    | 1         | 4.17%   |
| HP EliteBook 840 G6                  | 1         | 4.17%   |
| HP EliteBook 2560p                   | 1         | 4.17%   |
| HP 255 G8 Notebook PC                | 1         | 4.17%   |
| Google Cave                          | 1         | 4.17%   |
| F-Plus Mobile FLAPTOP r              | 1         | 4.17%   |
| Dell XPS 13 9305                     | 1         | 4.17%   |
| Dell Vostro 3350                     | 1         | 4.17%   |
| Dell Latitude E6540                  | 1         | 4.17%   |
| Dell Latitude E5540                  | 1         | 4.17%   |
| Dell Latitude 7490                   | 1         | 4.17%   |
| Dell Latitude 7390                   | 1         | 4.17%   |
| Dell Inspiron 5559                   | 1         | 4.17%   |
| ASUS X202E                           | 1         | 4.17%   |
| Alienware Area-51m                   | 1         | 4.17%   |
| Unknown                              | 1         | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 4         | 16.67%  |
| Lenovo ThinkPad       | 3         | 12.5%   |
| Dell XPS              | 3         | 12.5%   |
| HP EliteBook          | 2         | 8.33%   |
| TUXEDO Aura           | 1         | 4.17%   |
| Lenovo Legion         | 1         | 4.17%   |
| Infinix INBook        | 1         | 4.17%   |
| HP ProBook            | 1         | 4.17%   |
| HP 255                | 1         | 4.17%   |
| Google Cave           | 1         | 4.17%   |
| F-Plus Mobile FLAPTOP | 1         | 4.17%   |
| Dell Vostro           | 1         | 4.17%   |
| Dell Inspiron         | 1         | 4.17%   |
| ASUS X202E            | 1         | 4.17%   |
| Alienware Area-51m    | 1         | 4.17%   |
| Unknown               | 1         | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2023 | 4         | 16.67%  |
| 2022 | 3         | 12.5%   |
| 2021 | 3         | 12.5%   |
| 2020 | 3         | 12.5%   |
| 2018 | 2         | 8.33%   |
| 2015 | 2         | 8.33%   |
| 2013 | 2         | 8.33%   |
| 2019 | 1         | 4.17%   |
| 2016 | 1         | 4.17%   |
| 2014 | 1         | 4.17%   |
| 2012 | 1         | 4.17%   |
| 2011 | 1         | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 24        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 95.83%  |
| Yes  | 1         | 4.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 9         | 37.5%   |
| 8.01-16.0   | 9         | 37.5%   |
| 4.01-8.0    | 2         | 8.33%   |
| 32.01-64.0  | 2         | 8.33%   |
| 64.01-256.0 | 2         | 8.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 13        | 54.17%  |
| 0.01-0.5 | 5         | 20.83%  |
| 2.01-3.0 | 3         | 12.5%   |
| 1.01-2.0 | 3         | 12.5%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 54.17%  |
| 0      | 9         | 37.5%   |
| 2      | 2         | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 83.33%  |
| Yes       | 4         | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 66.67%  |
| No        | 8         | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 83.33%  |
| No        | 4         | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 25%     |
| Germany     | 3         | 12.5%   |
| Spain       | 2         | 8.33%   |
| France      | 2         | 8.33%   |
| Bulgaria    | 2         | 8.33%   |
| Switzerland | 1         | 4.17%   |
| Russia      | 1         | 4.17%   |
| Paraguay    | 1         | 4.17%   |
| Lithuania   | 1         | 4.17%   |
| Indonesia   | 1         | 4.17%   |
| Denmark     | 1         | 4.17%   |
| Cuba        | 1         | 4.17%   |
| Canada      | 1         | 4.17%   |
| Argentina   | 1         | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Roslindale                  | 2         | 8.33%   |
| Zurich                      | 1         | 4.17%   |
| Voskresensk                 | 1         | 4.17%   |
| Victoria                    | 1         | 4.17%   |
| Tsarevo                     | 1         | 4.17%   |
| Stuttgart                   | 1         | 4.17%   |
| Sofia                       | 1         | 4.17%   |
| San Nicolás de los Arroyos | 1         | 4.17%   |
| San Lorenzo                 | 1         | 4.17%   |
| Redondela                   | 1         | 4.17%   |
| Navalcarnero                | 1         | 4.17%   |
| Munich                      | 1         | 4.17%   |
| Leutkirch                   | 1         | 4.17%   |
| Jonava                      | 1         | 4.17%   |
| Jakarta                     | 1         | 4.17%   |
| Jacksonville                | 1         | 4.17%   |
| Havana                      | 1         | 4.17%   |
| Frederiksberg               | 1         | 4.17%   |
| Fos-sur-Mer                 | 1         | 4.17%   |
| Eureka                      | 1         | 4.17%   |
| Colombes                    | 1         | 4.17%   |
| Bothell                     | 1         | 4.17%   |
| Atlanta                     | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 4         | 4      | 23.53%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Seagate             | 2         | 2      | 11.76%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| Intel               | 2         | 2      | 11.76%  |
| Team                | 1         | 1      | 5.88%   |
| ShiJi               | 1         | 1      | 5.88%   |
| Fanxiang            | 1         | 1      | 5.88%   |
| China               | 1         | 1      | 5.88%   |
| Apple               | 1         | 1      | 5.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT1000MX500SSD1 1TB          | 2         | 11.76%  |
| Toshiba THNSNK128GVN8 M.2 2280 128GB | 1         | 5.88%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB  | 1         | 5.88%   |
| Team T253X1240G 240GB                | 1         | 5.88%   |
| ShiJi SSD 512GB                      | 1         | 5.88%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 5.88%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 5.88%   |
| Samsung SSD 860 PRO 512GB            | 1         | 5.88%   |
| Samsung SSD 830 Series 256GB         | 1         | 5.88%   |
| Intel SSDSCKKF512G8 SATA 512GB       | 1         | 5.88%   |
| Intel SSDSA2BW160G3H 160GB           | 1         | 5.88%   |
| Fanxiang S101 512GB                  | 1         | 5.88%   |
| Crucial CT240BX500SSD1 240GB         | 1         | 5.88%   |
| Crucial CT2000BX500SSD1 2TB          | 1         | 5.88%   |
| China SATA SSD 120GB                 | 1         | 5.88%   |
| Apple SSD SM0128G 121GB              | 1         | 5.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 4         | 4      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Intel               | 2         | 2      | 13.33%  |
| Team                | 1         | 1      | 6.67%   |
| ShiJi               | 1         | 1      | 6.67%   |
| Fanxiang            | 1         | 1      | 6.67%   |
| China               | 1         | 1      | 6.67%   |
| Apple               | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 14        | 15     | 87.5%   |
| HDD  | 2         | 2      | 12.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 15        | 17     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 9      | 52.94%  |
| 0.51-1.0   | 6         | 6      | 35.29%  |
| 1.01-2.0   | 2         | 2      | 11.76%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 37.5%   |
| 251-500    | 5         | 20.83%  |
| 21-50      | 3         | 12.5%   |
| 1-20       | 3         | 12.5%   |
| 501-1000   | 2         | 8.33%   |
| 1001-2000  | 1         | 4.17%   |
| 51-100     | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 21        | 87.5%   |
| 21-50   | 2         | 8.33%   |
| 101-250 | 1         | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba THNSNK128GVN8 M.2 2280 128GB | 1         | 1      | 25%     |
| ShiJi SSD 512GB                      | 1         | 1      | 25%     |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 25%     |
| Fanxiang S101 512GB                  | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 1         | 1      | 25%     |
| ShiJi    | 1         | 1      | 25%     |
| Seagate  | 1         | 1      | 25%     |
| Fanxiang | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 75%     |
| HDD  | 1         | 1      | 25%     |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 12        | 12     | 75%     |
| Malfunc | 3         | 4      | 18.75%  |
| Failed  | 1         | 1      | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 15        | 53.57%  |
| Samsung Electronics          | 3         | 10.71%  |
| AMD                          | 3         | 10.71%  |
| SK hynix                     | 2         | 7.14%   |
| Silicon Motion               | 1         | 3.57%   |
| Shenzhen Longsys Electronics | 1         | 3.57%   |
| Phison Electronics           | 1         | 3.57%   |
| Micron/Crucial Technology    | 1         | 3.57%   |
| Kingston Technology Company  | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 4         | 14.29%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 3         | 10.71%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 3         | 10.71%  |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 3         | 10.71%  |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 1         | 3.57%   |
| SK hynix BC511 NVMe SSD                                                                                            | 1         | 3.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 1         | 3.57%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 3.57%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                                         | 1         | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 1         | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 1         | 3.57%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 1         | 3.57%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                                               | 1         | 3.57%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                                               | 1         | 3.57%   |
| Intel SSD 600P Series                                                                                              | 1         | 3.57%   |
| Intel SATA Controller [RAID mode]                                                                                  | 1         | 3.57%   |
| Intel Jasper Lake SATA AHCI Controller                                                                             | 1         | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 1         | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 14        | 53.85%  |
| NVMe | 8         | 30.77%  |
| RAID | 4         | 15.38%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 75%     |
| AMD    | 6         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz            | 2         | 8.33%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz             | 1         | 4.17%   |
| Intel Core i9-9900 CPU @ 3.10GHz             | 1         | 4.17%   |
| Intel Core i7-8650U CPU @ 1.90GHz            | 1         | 4.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 4.17%   |
| Intel Core i7-4600U CPU @ 2.10GHz            | 1         | 4.17%   |
| Intel Core i7-2640M CPU @ 2.80GHz            | 1         | 4.17%   |
| Intel Core i7-2620M CPU @ 2.70GHz            | 1         | 4.17%   |
| Intel Core i5-8365U CPU @ 1.60GHz            | 1         | 4.17%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 4.17%   |
| Intel Core i5-4310M CPU @ 2.70GHz            | 1         | 4.17%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 4.17%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 1         | 4.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 1         | 4.17%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz           | 1         | 4.17%   |
| Intel Celeron N5095 @ 2.00GHz                | 1         | 4.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 1         | 4.17%   |
| AMD Ryzen 7 5825U with Radeon Graphics       | 1         | 4.17%   |
| AMD Ryzen 7 4700U with Radeon Graphics       | 1         | 4.17%   |
| AMD Ryzen 5 5600U with Radeon Graphics       | 1         | 4.17%   |
| AMD Ryzen 5 5600H with Radeon Graphics       | 1         | 4.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics       | 1         | 4.17%   |
| AMD PRO A10-8730B R5, 10 COMPUTE CORES 4C+6G | 1         | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 7         | 29.17%  |
| Intel Core i7 | 5         | 20.83%  |
| AMD Ryzen 5   | 3         | 12.5%   |
| Intel Core i3 | 2         | 8.33%   |
| AMD Ryzen 7   | 2         | 8.33%   |
| Other         | 1         | 4.17%   |
| Intel Core m3 | 1         | 4.17%   |
| Intel Core i9 | 1         | 4.17%   |
| Intel Celeron | 1         | 4.17%   |
| AMD PRO A10   | 1         | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 54.17%  |
| 4      | 5         | 20.83%  |
| 12     | 3         | 12.5%   |
| 8      | 2         | 8.33%   |
| 16     | 1         | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 70.83%  |
| 1      | 7         | 29.17%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 25%     |
| Zen 3       | 3         | 12.5%   |
| SandyBridge | 3         | 12.5%   |
| Haswell     | 3         | 12.5%   |
| Skylake     | 2         | 8.33%   |
| Unknown     | 2         | 8.33%   |
| Zen 2       | 1         | 4.17%   |
| TigerLake   | 1         | 4.17%   |
| IvyBridge   | 1         | 4.17%   |
| IceLake     | 1         | 4.17%   |
| Excavator   | 1         | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 67.86%  |
| AMD    | 6         | 21.43%  |
| Nvidia | 3         | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                     | 3         | 10.71%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 10.71%  |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 7.14%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                  | 1         | 3.57%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1         | 3.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 3.57%   |
| Intel UHD Graphics 620                                                    | 1         | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 3.57%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 3.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 3.57%   |
| Intel HD Graphics 6000                                                    | 1         | 3.57%   |
| Intel HD Graphics 515                                                     | 1         | 3.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 3.57%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 1         | 3.57%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 3.57%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 1         | 3.57%   |
| AMD Lucienne                                                              | 1         | 3.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 3.57%   |
| AMD Barcelo                                                               | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 66.67%  |
| 1 x AMD        | 4         | 16.67%  |
| 1 x Nvidia     | 1         | 4.17%   |
| Intel + Nvidia | 1         | 4.17%   |
| Intel + AMD    | 1         | 4.17%   |
| AMD + Nvidia   | 1         | 4.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 22        | 91.67%  |
| Proprietary | 2         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 79.17%  |
| 0.01-0.5   | 2         | 8.33%   |
| 7.01-8.0   | 1         | 4.17%   |
| 5.01-6.0   | 1         | 4.17%   |
| 0.51-1.0   | 1         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 8         | 33.33%  |
| BOE                 | 6         | 25%     |
| Samsung Electronics | 3         | 12.5%   |
| Sharp               | 2         | 8.33%   |
| InfoVision          | 1         | 4.17%   |
| HKC                 | 1         | 4.17%   |
| HannStar            | 1         | 4.17%   |
| Chimei Innolux      | 1         | 4.17%   |
| Apple               | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1481 1920x1080 290x170mm 13.2-inch               | 2         | 8.33%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 600x340mm 27.2-inch     | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 4.17%   |
| InfoVision LCD Monitor IVO8C69 1920x1080 310x170mm 13.9-inch          | 1         | 4.17%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                 | 1         | 4.17%   |
| HannStar LCD Monitor HSD1568 1920x1080 340x190mm 15.3-inch            | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN175F 1920x1080 380x210mm 17.1-inch      | 1         | 4.17%   |
| BOE LCD Monitor BOE0A40 2560x1600 340x210mm 15.7-inch                 | 1         | 4.17%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                 | 1         | 4.17%   |
| BOE LCD Monitor BOE0731 1366x768 260x140mm 11.6-inch                  | 1         | 4.17%   |
| BOE LCD Monitor BOE06EE 1920x1080 310x170mm 13.9-inch                 | 1         | 4.17%   |
| BOE LCD Monitor BOE06DF 1920x1080 310x170mm 13.9-inch                 | 1         | 4.17%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO35EC 1366x768 340x190mm 15.3-inch         | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch         | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch         | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO206C 1366x768 280x160mm 12.7-inch         | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO142D 1920x1080 290x170mm 13.2-inch        | 1         | 4.17%   |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                  | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 15        | 62.5%   |
| 1366x768 (WXGA)  | 7         | 29.17%  |
| 2560x1600        | 1         | 4.17%   |
| 1440x900 (WXGA+) | 1         | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 9         | 37.5%   |
| 15     | 7         | 29.17%  |
| 12     | 4         | 16.67%  |
| 11     | 2         | 8.33%   |
| 27     | 1         | 4.17%   |
| 17     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 45.83%  |
| 201-300     | 11        | 45.83%  |
| 501-600     | 1         | 4.17%   |
| 351-400     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 91.67%  |
| 16/10 | 2         | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 6         | 25%     |
| 81-90          | 5         | 20.83%  |
| 71-80          | 4         | 16.67%  |
| 61-70          | 4         | 16.67%  |
| 51-60          | 2         | 8.33%   |
| 301-350        | 1         | 4.17%   |
| 121-130        | 1         | 4.17%   |
| 111-120        | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 15        | 62.5%   |
| 161-240 | 6         | 25%     |
| 101-120 | 2         | 8.33%   |
| 51-100  | 1         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 22        | 91.67%  |
| 0     | 2         | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 19        | 48.72%  |
| Realtek Semiconductor             | 9         | 23.08%  |
| Qualcomm Atheros                  | 4         | 10.26%  |
| Broadcom                          | 3         | 7.69%   |
| TP-Link                           | 2         | 5.13%   |
| Huawei Technologies               | 1         | 2.56%   |
| Ericsson Business Mobile Networks | 1         | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller      | 6         | 12.5%   |
| Intel Wireless 7265                                                         | 4         | 8.33%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 4.17%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 4.17%   |
| Intel Wireless 7260                                                         | 2         | 4.17%   |
| Intel Wireless 3160                                                         | 2         | 4.17%   |
| Intel Ethernet Connection I218-LM                                           | 2         | 4.17%   |
| Intel Ethernet Connection (4) I219-LM                                       | 2         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 2         | 4.17%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1         | 2.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 1         | 2.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 2.08%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                 | 1         | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 2.08%   |
| Realtek Killer E3000 2.5GbE Controller                                      | 1         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 1         | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 2.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                       | 1         | 2.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                   | 1         | 2.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                             | 1         | 2.08%   |
| Intel Ethernet Connection I217-LM                                           | 1         | 2.08%   |
| Intel Ethernet Connection (6) I219-LM                                       | 1         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 1         | 2.08%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                            | 1         | 2.08%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 2.08%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                | 1         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                           | 1         | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 58.62%  |
| Qualcomm Atheros      | 4         | 13.79%  |
| Realtek Semiconductor | 3         | 10.34%  |
| Broadcom              | 3         | 10.34%  |
| TP-Link               | 2         | 6.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 4         | 13.79%  |
| Intel Wi-Fi 6 AX200                                            | 3         | 10.34%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 6.9%    |
| Intel Wireless 8265 / 8275                                     | 2         | 6.9%    |
| Intel Wireless 7260                                            | 2         | 6.9%    |
| Intel Wireless 3160                                            | 2         | 6.9%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 3.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 3.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.45%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 3.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 3.45%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 3.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 50%     |
| Realtek Semiconductor | 7         | 43.75%  |
| Qualcomm Atheros      | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6         | 37.5%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 12.5%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 6.25%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 6.25%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 6.25%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 57.78%  |
| Ethernet | 16        | 35.56%  |
| Unknown  | 2         | 4.44%   |
| Modem    | 1         | 2.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 76.19%  |
| Ethernet | 5         | 23.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 70.83%  |
| 1     | 7         | 29.17%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 75%     |
| Realtek Semiconductor           | 2         | 10%     |
| Qualcomm Atheros Communications | 2         | 10%     |
| Lite-On Technology              | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 9         | 45%     |
| Intel AX200 Bluetooth                          | 3         | 15%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 10%     |
| Realtek Bluetooth Adapter                      | 1         | 5%      |
| Realtek Bluetooth 4.2 Adapter                  | 1         | 5%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1         | 1         | 5%      |
| Qualcomm Atheros AR3011 Bluetooth              | 1         | 5%      |
| Lite-On Atheros Bluetooth                      | 1         | 5%      |
| Intel AX210 Bluetooth                          | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 19        | 61.29%  |
| AMD                 | 6         | 19.35%  |
| Nvidia              | 3         | 9.68%   |
| Microsoft           | 1         | 3.23%   |
| GN Netcom           | 1         | 3.23%   |
| C-Media Electronics | 1         | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 15%     |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 5         | 12.5%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 10%     |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 7.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5%      |
| Intel 8 Series HD Audio Controller                                         | 2         | 5%      |
| Nvidia TU104 HD Audio Controller                                           | 1         | 2.5%    |
| Nvidia GM200 High Definition Audio                                         | 1         | 2.5%    |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 2.5%    |
| Microsoft LifeChat LX-3000 Headset                                         | 1         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.5%    |
| Intel Jasper Lake HD Audio                                                 | 1         | 2.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.5%    |
| GN Netcom Jabra EVOLVE 20 SE MS                                            | 1         | 2.5%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 2.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 24.14%  |
| SK hynix            | 6         | 20.69%  |
| Micron Technology   | 5         | 17.24%  |
| Kingston            | 3         | 10.34%  |
| Crucial             | 3         | 10.34%  |
| Ramaxel Technology  | 2         | 6.9%    |
| Unknown             | 2         | 6.9%    |
| Corsair             | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 2         | 6.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 6.67%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 6.67%   |
| Unknown                                                          | 2         | 6.67%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 3.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.33%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 3.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 3.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 3.33%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 3.33%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 3.33%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.33%   |
| Samsung RAM D24D4S7S8MA-8 8GB Row Of Chips LPDDR4 3733MT/s       | 1         | 3.33%   |
| Ramaxel RAM RMSA3310MF96HAF-3200 8GB SODIMM DDR4 3200MT/s        | 1         | 3.33%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 3.33%   |
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s | 1         | 3.33%   |
| Micron RAM MT52L256M32D1PF-10 2GB LPDDR3 1867MT/s                | 1         | 3.33%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| Micron RAM 8KTF51264HZ-1G4E1 4GB SODIMM DDR3 1333MT/s            | 1         | 3.33%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 3.33%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s          | 1         | 3.33%   |
| Kingston RAM 99U5428-049.A00LF 4GB SODIMM DDR3 1600MT/s          | 1         | 3.33%   |
| Kingston RAM 9905428-093.A00LF 8GB SODIMM DDR3 1333MT/s          | 1         | 3.33%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s        | 1         | 3.33%   |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s          | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 41.67%  |
| DDR3   | 8         | 33.33%  |
| LPDDR4 | 3         | 12.5%   |
| LPDDR3 | 3         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 75%     |
| Row Of Chips | 5         | 20.83%  |
| Unknown      | 1         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 42.31%  |
| 4096  | 7         | 26.92%  |
| 32768 | 3         | 11.54%  |
| 16384 | 3         | 11.54%  |
| 2048  | 2         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 6         | 23.08%  |
| 1600  | 6         | 23.08%  |
| 1867  | 3         | 11.54%  |
| 2667  | 2         | 7.69%   |
| 2400  | 2         | 7.69%   |
| 1334  | 2         | 7.69%   |
| 1333  | 2         | 7.69%   |
| 4267  | 1         | 3.85%   |
| 3733  | 1         | 3.85%   |
| 2133  | 1         | 3.85%   |

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
| Microdia                      | 7         | 35%     |
| Chicony Electronics           | 4         | 20%     |
| Lite-On Technology            | 2         | 10%     |
| IMC Networks                  | 2         | 10%     |
| USB Camera                    | 1         | 5%      |
| Sunplus Innovation Technology | 1         | 5%      |
| Realtek Semiconductor         | 1         | 5%      |
| Intel                         | 1         | 5%      |
| Bison Electronics             | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Laptop_Integrated_Webcam_HD     | 2         | 10%     |
| Microdia Integrated Webcam HD            | 2         | 10%     |
| USB Camera USB Camera                    | 1         | 5%      |
| Sunplus Integrated_Webcam_HD             | 1         | 5%      |
| Realtek Integrated Webcam HD             | 1         | 5%      |
| Microdia USB Camera                      | 1         | 5%      |
| Microdia Integrated_Webcam_HD            | 1         | 5%      |
| Microdia Integrated Webcam               | 1         | 5%      |
| Lite-On Realtek PC Camera                | 1         | 5%      |
| Lite-On HP HD Camera                     | 1         | 5%      |
| Intel RealSense 3D Camera (Front F200)   | 1         | 5%      |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 5%      |
| IMC Networks USB 2.0 UVC HD Webcam       | 1         | 5%      |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 5%      |
| Chicony Integrated HP HD Webcam          | 1         | 5%      |
| Chicony Integrated Camera                | 1         | 5%      |
| Chicony HP HD Camera                     | 1         | 5%      |
| Bison SunplusIT INC. Integrated Camera   | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 44.44%  |
| Synaptics                  | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |
| FocalTech Systems          | 1         | 11.11%  |
| Fingerprint Cards          | 1         | 11.11%  |
| Elan Microelectronics      | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 11.11%  |
| Synaptics Fingerprint reader [HP G6]              | 1         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device               | 1         | 11.11%  |
| FocalTech Systems Fingerprint Reader              | 1         | 11.11%  |
| Fingerprint Cards FPC Fingerprint Reader          | 1         | 11.11%  |
| Elan Fingerprint Sensor                           | 1         | 11.11%  |

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
| 2     | 12        | 50%     |
| 3     | 5         | 20.83%  |
| 1     | 4         | 16.67%  |
| 5     | 2         | 8.33%   |
| 0     | 1         | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 18        | 37.5%   |
| Bluetooth                | 13        | 27.08%  |
| Fingerprint reader       | 8         | 16.67%  |
| Net/wireless             | 5         | 10.42%  |
| Network                  | 2         | 4.17%   |
| Card reader              | 2         | 4.17%   |

