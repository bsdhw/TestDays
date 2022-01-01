helloSystem 0.7.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor  | Model                       | Probe                                                     | Date         |
|---------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell    | Latitude E6540              | [97d152656e](https://bsd-hardware.info/?probe=97d152656e) | Dec 31, 2021 |
| HP      | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Acer    | Aspire 5742G                | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| ASUSTek | S550CA                      | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Lenovo  | ThinkPad E580 20KS005BRI    | [b533989df5](https://bsd-hardware.info/?probe=b533989df5) | Dec 29, 2021 |
| Dell    | Inspiron 3521               | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Lenovo  | ThinkPad T460 20FMS75800    | [5f17e74f2f](https://bsd-hardware.info/?probe=5f17e74f2f) | Dec 27, 2021 |
| Acer    | Aspire 5742G                | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Acer    | TravelMate 5760G            | [46204b90d0](https://bsd-hardware.info/?probe=46204b90d0) | Dec 24, 2021 |
| Lenovo  | ThinkPad SL510 2847R96      | [b0a9802877](https://bsd-hardware.info/?probe=b0a9802877) | Dec 22, 2021 |
| Lenovo  | ThinkPad T410 2537EA8       | [8b457cd635](https://bsd-hardware.info/?probe=8b457cd635) | Dec 22, 2021 |
| Lenovo  | ThinkPad X250 20CLS1WP01    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| Toshiba | Satellite C50-B             | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| Samsung | 305E4A/305E5A/305E7A        | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Lenovo  | ThinkPad X270 W10DG 20K5... | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| HP      | Pavilion Gaming Laptop 1... | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP      | Pavilion Gaming Laptop 1... | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| Toshiba | Satellite L550              | [977298a601](https://bsd-hardware.info/?probe=977298a601) | Dec 20, 2021 |
| ASUSTek | N56VB                       | [f53b3fba5c](https://bsd-hardware.info/?probe=f53b3fba5c) | Dec 20, 2021 |
| HP      | 15 Notebook PC              | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| Lenovo  | IdeaPad 510-15IKB 80SV      | [6321f4bd3a](https://bsd-hardware.info/?probe=6321f4bd3a) | Dec 20, 2021 |
| Dell    | Latitude E5470              | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| HP      | ZBook Studio G4             | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| Apple   | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| ASUSTek | X540LA                      | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek | X540LA                      | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer    | Swift SF314-52              | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Toshiba | Satellite S55t-B            | [f6983391aa](https://bsd-hardware.info/?probe=f6983391aa) | Nov 28, 2021 |
| Lenovo  | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Lenovo  | V310-14IKB 80T2             | [f5421b8fe0](https://bsd-hardware.info/?probe=f5421b8fe0) | Nov 23, 2021 |
| Toshiba | Satellite C640              | [2d60f00479](https://bsd-hardware.info/?probe=2d60f00479) | Nov 17, 2021 |
| Toshiba | Satellite C640              | [89a9551487](https://bsd-hardware.info/?probe=89a9551487) | Nov 17, 2021 |
| Lenovo  | ThinkPad T60 1951FEG        | [e2d5391a1a](https://bsd-hardware.info/?probe=e2d5391a1a) | Nov 14, 2021 |
| ASUSTek | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| Apple   | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| HP      | Pavilion Gaming Laptop 1... | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 32        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 32        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 32        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 32        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 32        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 30        | 93.75%  |
| BIOS | 2         | 6.25%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 19        | 59.38%  |
| Zfs    | 13        | 40.63%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 32        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 31.25%  |
| Hewlett-Packard     | 5         | 15.63%  |
| Toshiba             | 4         | 12.5%   |
| ASUSTek Computer    | 4         | 12.5%   |
| Dell                | 3         | 9.38%   |
| Acer                | 3         | 9.38%   |
| Apple               | 2         | 6.25%   |
| Samsung Electronics | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B              | 1         | 3.13%   |
| Toshiba Satellite L550                | 1         | 3.13%   |
| Toshiba Satellite C640                | 1         | 3.13%   |
| Toshiba Satellite C50-B               | 1         | 3.13%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 3.13%   |
| Lenovo V310-14IKB 80T2                | 1         | 3.13%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01 | 1         | 3.13%   |
| Lenovo ThinkPad X250 20CLS1WP01       | 1         | 3.13%   |
| Lenovo ThinkPad X240 20AMS2QDOC       | 1         | 3.13%   |
| Lenovo ThinkPad T60 1951FEG           | 1         | 3.13%   |
| Lenovo ThinkPad T460 20FMS75800       | 1         | 3.13%   |
| Lenovo ThinkPad T410 2537EA8          | 1         | 3.13%   |
| Lenovo ThinkPad SL510 2847R96         | 1         | 3.13%   |
| Lenovo ThinkPad E580 20KS005BRI       | 1         | 3.13%   |
| Lenovo IdeaPad 510-15IKB 80SV         | 1         | 3.13%   |
| HP ZBook Studio G4                    | 1         | 3.13%   |
| HP ProBook 655 G1                     | 1         | 3.13%   |
| HP Pavilion Gaming Laptop 16-a0xxx    | 1         | 3.13%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 1         | 3.13%   |
| HP 15 Notebook PC                     | 1         | 3.13%   |
| Dell Latitude E6540                   | 1         | 3.13%   |
| Dell Latitude E5470                   | 1         | 3.13%   |
| Dell Inspiron 3521                    | 1         | 3.13%   |
| ASUS X540LA                           | 1         | 3.13%   |
| ASUS S550CA                           | 1         | 3.13%   |
| ASUS N56VB                            | 1         | 3.13%   |
| ASUS K52Jc                            | 1         | 3.13%   |
| Apple MacBookAir5,1                   | 1         | 3.13%   |
| Apple MacBookAir1,1                   | 1         | 3.13%   |
| Acer TravelMate 5760G                 | 1         | 3.13%   |
| Acer Swift SF314-52                   | 1         | 3.13%   |
| Acer Aspire 5742G                     | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 8         | 25%     |
| Toshiba Satellite | 4         | 12.5%   |
| HP Pavilion       | 2         | 6.25%   |
| Dell Latitude     | 2         | 6.25%   |
| Samsung 305E4A    | 1         | 3.13%   |
| Lenovo V310-14IKB | 1         | 3.13%   |
| Lenovo IdeaPad    | 1         | 3.13%   |
| HP ZBook          | 1         | 3.13%   |
| HP ProBook        | 1         | 3.13%   |
| HP 15             | 1         | 3.13%   |
| Dell Inspiron     | 1         | 3.13%   |
| ASUS X540LA       | 1         | 3.13%   |
| ASUS S550CA       | 1         | 3.13%   |
| ASUS N56VB        | 1         | 3.13%   |
| ASUS K52Jc        | 1         | 3.13%   |
| Apple MacBookAir5 | 1         | 3.13%   |
| Apple MacBookAir1 | 1         | 3.13%   |
| Acer TravelMate   | 1         | 3.13%   |
| Acer Swift        | 1         | 3.13%   |
| Acer Aspire       | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 21.88%  |
| 2020 | 3         | 9.38%   |
| 2015 | 3         | 9.38%   |
| 2013 | 3         | 9.38%   |
| 2012 | 3         | 9.38%   |
| 2010 | 3         | 9.38%   |
| 2018 | 2         | 6.25%   |
| 2017 | 2         | 6.25%   |
| 2011 | 2         | 6.25%   |
| 2016 | 1         | 3.13%   |
| 2014 | 1         | 3.13%   |
| 2008 | 1         | 3.13%   |
| 2006 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 32        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 43.75%  |
| 8.01-16.0  | 8         | 25%     |
| 16.01-24.0 | 7         | 21.88%  |
| 2.01-3.0   | 2         | 6.25%   |
| 3.01-4.0   | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 22        | 68.75%  |
| 0.51-1.0 | 9         | 28.13%  |
| 1.01-2.0 | 1         | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 71.88%  |
| 2      | 8         | 25%     |
| 3      | 1         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 53.13%  |
| Yes       | 15        | 46.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 90.63%  |
| No        | 3         | 9.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 65.63%  |
| No        | 11        | 34.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 18.75%  |
| Romania     | 3         | 9.38%   |
| Germany     | 3         | 9.38%   |
| Ukraine     | 2         | 6.25%   |
| Poland      | 2         | 6.25%   |
| Peru        | 2         | 6.25%   |
| Netherlands | 2         | 6.25%   |
| Indonesia   | 2         | 6.25%   |
| Denmark     | 2         | 6.25%   |
| Vietnam     | 1         | 3.13%   |
| UK          | 1         | 3.13%   |
| Sweden      | 1         | 3.13%   |
| Russia      | 1         | 3.13%   |
| Norway      | 1         | 3.13%   |
| Hungary     | 1         | 3.13%   |
| France      | 1         | 3.13%   |
| Bulgaria    | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Warsaw           | 2         | 6.25%   |
| Lima             | 2         | 6.25%   |
| Jakarta          | 2         | 6.25%   |
| Zaporizhzhya     | 1         | 3.13%   |
| V?¤ster??s       | 1         | 3.13%   |
| Ugarchin         | 1         | 3.13%   |
| Torokszentmiklos | 1         | 3.13%   |
| Suceava          | 1         | 3.13%   |
| Sevastopol       | 1         | 3.13%   |
| Seattle          | 1         | 3.13%   |
| San Antonio      | 1         | 3.13%   |
| Pruszcz Gdanski  | 1         | 3.13%   |
| Patterson        | 1         | 3.13%   |
| Oldenburg        | 1         | 3.13%   |
| Odense           | 1         | 3.13%   |
| Nesttun          | 1         | 3.13%   |
| Moscow           | 1         | 3.13%   |
| Longfield        | 1         | 3.13%   |
| Hvidovre         | 1         | 3.13%   |
| Hoogeveen        | 1         | 3.13%   |
| Hicksville       | 1         | 3.13%   |
| Hanoi            | 1         | 3.13%   |
| Hackettstown     | 1         | 3.13%   |
| Donauw?¶rth      | 1         | 3.13%   |
| Dijon            | 1         | 3.13%   |
| Detmold          | 1         | 3.13%   |
| Cluj-Napoca      | 1         | 3.13%   |
| Bucharest        | 1         | 3.13%   |
| Amsterdam        | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 18.6%   |
| Toshiba             | 5         | 5      | 11.63%  |
| Kingston            | 5         | 5      | 11.63%  |
| Samsung Electronics | 4         | 4      | 9.3%    |
| Seagate             | 3         | 3      | 6.98%   |
| SanDisk             | 3         | 3      | 6.98%   |
| Intel               | 3         | 4      | 6.98%   |
| HGST                | 2         | 2      | 4.65%   |
| Crucial             | 2         | 2      | 4.65%   |
| Transcend           | 1         | 1      | 2.33%   |
| SK Hynix            | 1         | 1      | 2.33%   |
| KingSpec            | 1         | 1      | 2.33%   |
| Integral            | 1         | 1      | 2.33%   |
| Hitachi             | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB          | 2         | 4.55%   |
| Kingston SA400S37120G 120GB       | 2         | 4.55%   |
| HGST HTS545050A7E680 500GB        | 2         | 4.55%   |
| Crucial CT500MX500SSD1 500GB      | 2         | 4.55%   |
| WDC WDS120G2G0A-00JH30 120GB      | 1         | 2.27%   |
| WDC WDBNCE5000PNC 500GB           | 1         | 2.27%   |
| WDC WD5000LPLX-60ZNTT1 500GB      | 1         | 2.27%   |
| WDC WD5000BPVT-22HXZT3 500GB      | 1         | 2.27%   |
| WDC WD5000BPKX-22HPJT0 500GB      | 1         | 2.27%   |
| WDC WD1200BEVS-07RST0 120GB       | 1         | 2.27%   |
| WDC WD10SDZW-11UMGS0 1TB          | 1         | 2.27%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 2.27%   |
| Transcend TS240GMTS420S 240GB     | 1         | 2.27%   |
| Toshiba MQ01ABD100 1TB            | 1         | 2.27%   |
| Toshiba MQ01ABD075 752GB          | 1         | 2.27%   |
| Toshiba MK3265GSXN 320GB          | 1         | 2.27%   |
| SK Hynix HFS256G39TND-N210A 256GB | 1         | 2.27%   |
| Seagate ST980813AS 80GB           | 1         | 2.27%   |
| Seagate ST9640320AS 640GB         | 1         | 2.27%   |
| Seagate ST9320423AS 320GB         | 1         | 2.27%   |
| SanDisk SDSSDH3 512G              | 1         | 2.27%   |
| SanDisk SD8TB8U512G1001 512GB     | 1         | 2.27%   |
| SanDisk SD6SB1M064G 64GB          | 1         | 2.27%   |
| Samsung SSD 980 PRO 1TB           | 1         | 2.27%   |
| Samsung MZVLW256HEHP-000L7 256GB  | 1         | 2.27%   |
| Samsung MZNLN256HMHQ-000H7 256GB  | 1         | 2.27%   |
| Samsung HS082HB 80GB              | 1         | 2.27%   |
| Kingston SA400S37240G 240GB       | 1         | 2.27%   |
| Kingston RBUSNS8154P3256GJ1 256GB | 1         | 2.27%   |
| Kingston OM8SBP3512K-AH 512GB     | 1         | 2.27%   |
| KingSpec NT-256 256GB             | 1         | 2.27%   |
| Intel SSDSC2KF180H6L 180GB        | 1         | 2.27%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 2.27%   |
| Intel HBRPEKNX0202AHO 32GB        | 1         | 2.27%   |
| Intel HBRPEKNX0202AH 512GB        | 1         | 2.27%   |
| Integral V Series SATA SSD 120GB  | 1         | 2.27%   |
| Hitachi HTS541680J9SA00 80GB      | 1         | 2.27%   |
| HP SSD S700 Pro 512GB             | 1         | 2.27%   |
| Apple SSD TS128E 121GB            | 1         | 2.27%   |
| A-DATA SP550 240GB                | 1         | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 33.33%  |
| Toshiba             | 5         | 5      | 27.78%  |
| Seagate             | 3         | 3      | 16.67%  |
| HGST                | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 15%     |
| Kingston            | 3         | 3      | 15%     |
| WDC                 | 2         | 2      | 10%     |
| Intel               | 2         | 2      | 10%     |
| Crucial             | 2         | 2      | 10%     |
| Transcend           | 1         | 1      | 5%      |
| SK Hynix            | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| KingSpec            | 1         | 1      | 5%      |
| Integral            | 1         | 1      | 5%      |
| Hewlett-Packard     | 1         | 1      | 5%      |
| Apple               | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 16        | 20     | 43.24%  |
| HDD  | 16        | 18     | 43.24%  |
| NVMe | 5         | 6      | 13.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 38     | 85.71%  |
| NVMe | 5         | 6      | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 30     | 75.76%  |
| 0.51-1.0   | 8         | 8      | 24.24%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 19        | 59.38%  |
| 251-500    | 6         | 18.75%  |
| 21-50      | 2         | 6.25%   |
| 101-250    | 2         | 6.25%   |
| 501-1000   | 2         | 6.25%   |
| 51-100     | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 32        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB     | 1         | 1      | 11.11%  |
| WDC WD5000BPVT-22HXZT3 500GB     | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD075 752GB         | 1         | 1      | 11.11%  |
| Toshiba MK3265GSXN 320GB         | 1         | 1      | 11.11%  |
| Seagate ST9640320AS 640GB        | 1         | 1      | 11.11%  |
| Seagate ST9320423AS 320GB        | 1         | 1      | 11.11%  |
| Samsung Electronics HS082HB 80GB | 1         | 1      | 11.11%  |
| HGST HTS545050A7E680 500GB       | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 100%    |

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
| Works    | 23        | 34     | 69.7%   |
| Malfunc  | 9         | 9      | 27.27%  |
| Detected | 1         | 1      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 28        | 80%     |
| AMD                         | 3         | 8.57%   |
| Samsung Electronics         | 2         | 5.71%   |
| Kingston Technology Company | 2         | 5.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 15.79%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 10.53%  |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 10.53%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 7.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 5.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 5.26%   |
| Unknown                                                                          | 2         | 5.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 2.63%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.63%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 78.95%  |
| NVMe | 5         | 13.16%  |
| IDE  | 2         | 5.26%   |
| RAID | 1         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 90.63%  |
| AMD    | 3         | 9.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz         | 2         | 6.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 2         | 6.25%   |
| Intel Core i5-5200U CPU @ 2.20GHz         | 2         | 6.25%   |
| Intel Pentium CPU N3530 @ 2.16GHz         | 1         | 3.13%   |
| Intel CPU Version                         | 1         | 3.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 1         | 3.13%   |
| Intel Core i7-6600U CPU @ 2.60GHz         | 1         | 3.13%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz        | 1         | 3.13%   |
| Intel Core i7-4600U CPU @ 2.10GHz         | 1         | 3.13%   |
| Intel Core i7-3630QM CPU @ 2.40GHz        | 1         | 3.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 1         | 3.13%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz        | 1         | 3.13%   |
| Intel Core i5-3317U CPU @ 1.70GHz         | 1         | 3.13%   |
| Intel Core i5-10300H CPU @ 2.50GHz        | 1         | 3.13%   |
| Intel Core i5 CPU M 520 @ 2.40GHz         | 1         | 3.13%   |
| Intel Core i3-4005U CPU @ 1.70GHz         | 1         | 3.13%   |
| Intel Core i3-3227U CPU @ 1.90GHz         | 1         | 3.13%   |
| Intel Core i3-3217U CPU @ 1.80GHz         | 1         | 3.13%   |
| Intel Core i3-2330M CPU @ 2.20GHz         | 1         | 3.13%   |
| Intel Core i3 CPU M 390 @ 2.67GHz         | 1         | 3.13%   |
| Intel Core i3 CPU M 370 @ 2.40GHz         | 1         | 3.13%   |
| Intel Core i3 CPU M 350 @ 2.27GH          | 1         | 3.13%   |
| Intel Core i3 CPU M 330 @ 2.13GHz         | 1         | 3.13%   |
| Intel Core 2 Duo CPU P7500 @ 1.60GHz      | 1         | 3.13%   |
| Intel Core 2 CPU                          | 1         | 3.13%   |
| Intel Celeron CPU N3050 @ 1.60GHz         | 1         | 3.13%   |
| AMD Ryzen 5 5600H with Radeon Graphics    | 1         | 3.13%   |
| AMD A6-3420M APU with Radeon HD Graphics  | 1         | 3.13%   |
| AMD A10-5750M APU with Radeon HD Graphics | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 11        | 34.38%  |
| Intel Core i3    | 8         | 25%     |
| Intel Core i7    | 5         | 15.63%  |
| Other            | 1         | 3.13%   |
| Intel Pentium    | 1         | 3.13%   |
| Intel Core 2 Duo | 1         | 3.13%   |
| Intel Core 2     | 1         | 3.13%   |
| Intel Celeron    | 1         | 3.13%   |
| AMD Ryzen 5      | 1         | 3.13%   |
| AMD A6           | 1         | 3.13%   |
| AMD A10          | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 62.5%   |
| 4       | 9         | 28.13%  |
| Unknown | 2         | 6.25%   |
| 12      | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 96.88%  |
| 2      | 1         | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 23        | 71.88%  |
| 1       | 7         | 21.88%  |
| Unknown | 2         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Westmere    | 5         | 15.63%  |
| KabyLake    | 5         | 15.63%  |
| IvyBridge   | 4         | 12.5%   |
| Skylake     | 3         | 9.38%   |
| Haswell     | 3         | 9.38%   |
| Silvermont  | 2         | 6.25%   |
| Core        | 2         | 6.25%   |
| Broadwell   | 2         | 6.25%   |
| Zen 3       | 1         | 3.13%   |
| SandyBridge | 1         | 3.13%   |
| Piledriver  | 1         | 3.13%   |
| Penryn      | 1         | 3.13%   |
| K10 Llano   | 1         | 3.13%   |
| CometLake   | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 67.5%   |
| AMD    | 7         | 17.5%   |
| Nvidia | 6         | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 9.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 7.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 7.14%   |
| Intel UHD Graphics 620                                                                   | 2         | 4.76%   |
| Intel HD Graphics 620                                                                    | 2         | 4.76%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 4.76%   |
| Nvidia TU117M                                                                            | 1         | 2.38%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.38%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 2.38%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 2.38%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 2.38%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.38%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.38%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.38%   |
| Intel HD Graphics 630                                                                    | 1         | 2.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.38%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 2.38%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 2.38%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 2.38%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 2.38%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 2.38%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 2.38%   |
| AMD Cezanne                                                                              | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 53.13%  |
| Intel + Nvidia | 4         | 12.5%   |
| 2 x Intel      | 3         | 9.38%   |
| Intel + AMD    | 3         | 9.38%   |
| 1 x AMD        | 3         | 9.38%   |
| 1 x Nvidia     | 1         | 3.13%   |
| AMD + Nvidia   | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 31        | 96.88%  |
| Proprietary | 1         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 87.5%   |
| 0.51-1.0   | 3         | 9.38%   |
| 0.01-0.5   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 22.86%  |
| Samsung Electronics     | 6         | 17.14%  |
| Chimei Innolux          | 5         | 14.29%  |
| BOE                     | 5         | 14.29%  |
| Lenovo                  | 4         | 11.43%  |
| AU Optronics            | 2         | 5.71%   |
| Apple                   | 2         | 5.71%   |
| Chi Mei Optoelectronics | 1         | 2.86%   |
| BenQ                    | 1         | 2.86%   |
| Ancor Communications    | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 240x130mm 10.7-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 2.86%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 2.86%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch             | 1         | 2.86%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD01CA 1600x900 380x210mm 17.1-inch              | 1         | 2.86%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch                 | 1         | 2.86%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 1         | 2.86%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                  | 1         | 2.86%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 360x200mm 16.2-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 340x190mm 15.3-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 310x170mm 13.9-inch         | 1         | 2.86%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 2.86%   |
| BOE LCD Monitor BOE06FF 1920x1080 340x190mm 15.3-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                     | 1         | 2.86%   |
| BOE LCD Monitor BOE0662 1366x768 340x190mm 15.3-inch                     | 1         | 2.86%   |
| BOE LCD Monitor BOE065E 1920x1080 340x190mm 15.3-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE0653 1920x1080 310x170mm 13.9-inch                    | 1         | 2.86%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 340x190mm 15.3-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 1         | 2.86%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 1         | 2.86%   |
| Apple Color LCD APP9C6F 1280x800 290x190mm 13.6-inch                     | 1         | 2.86%   |
| Ancor Communications PB248 ACI24A3 1920x1200 520x320mm 24.0-inch         | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 15        | 45.45%  |
| 1920x1080 (FHD)   | 12        | 36.36%  |
| 1280x800 (WXGA)   | 2         | 6.06%   |
| 2560x1440 (QHD)   | 1         | 3.03%   |
| 1920x1200 (WUXGA) | 1         | 3.03%   |
| 1600x900 (HD+)    | 1         | 3.03%   |
| 1024x768 (XGA)    | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 48.57%  |
| 13     | 6         | 17.14%  |
| 12     | 3         | 8.57%   |
| 27     | 2         | 5.71%   |
| 14     | 2         | 5.71%   |
| 24     | 1         | 2.86%   |
| 23     | 1         | 2.86%   |
| 17     | 1         | 2.86%   |
| 16     | 1         | 2.86%   |
| 11     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 62.86%  |
| 201-300     | 7         | 20%     |
| 501-600     | 4         | 11.43%  |
| 351-400     | 2         | 5.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 87.5%   |
| 16/10 | 2         | 6.25%   |
| 4/3   | 1         | 3.13%   |
| 3/2   | 1         | 3.13%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 15        | 42.86%  |
| 81-90          | 7         | 20%     |
| 61-70          | 3         | 8.57%   |
| 101-110        | 3         | 8.57%   |
| 301-350        | 2         | 5.71%   |
| 51-60          | 1         | 2.86%   |
| 251-300        | 1         | 2.86%   |
| 201-250        | 1         | 2.86%   |
| 121-130        | 1         | 2.86%   |
| 111-120        | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 42.86%  |
| 121-160 | 14        | 40%     |
| 51-100  | 5         | 14.29%  |
| 161-240 | 1         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 27        | 84.38%  |
| 2     | 4         | 12.5%   |
| 0     | 1         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 29.41%  |
| Intel                 | 15        | 29.41%  |
| Qualcomm Atheros      | 11        | 21.57%  |
| Broadcom              | 6         | 11.76%  |
| NetGear               | 1         | 1.96%   |
| JMicron Technology    | 1         | 1.96%   |
| Google                | 1         | 1.96%   |
| Dell                  | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 14.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 4.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 4.69%   |
| Intel Wireless 8260                                               | 3         | 4.69%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 4.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.13%   |
| Intel Wireless 7265                                               | 2         | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.56%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 1.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.56%   |
| Intel Wireless 7260                                               | 1         | 1.56%   |
| Intel Wireless 3160                                               | 1         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 1.56%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.56%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.56%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.56%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.56%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.56%   |
| Dell Hub of E-Port Replicator                                     | 1         | 1.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.56%   |
| Broadcom BCM43227 802.11b/g/n                                     | 1         | 1.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.56%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 42.86%  |
| Qualcomm Atheros      | 10        | 28.57%  |
| Broadcom              | 5         | 14.29%  |
| Realtek Semiconductor | 3         | 8.57%   |
| NetGear               | 1         | 2.86%   |
| Dell                  | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 8.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 8.57%   |
| Intel Wireless 8260                                            | 3         | 8.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 5.71%   |
| Intel Wireless 7265                                            | 2         | 5.71%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 5.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 5.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.86%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 2.86%   |
| Intel Wireless 7260                                            | 1         | 2.86%   |
| Intel Wireless 3160                                            | 1         | 2.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.86%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 2.86%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.86%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.86%   |
| Dell Hub of E-Port Replicator                                  | 1         | 2.86%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.86%   |
| Broadcom BCM43227 802.11b/g/n                                  | 1         | 2.86%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 2.86%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.86%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 48.28%  |
| Intel                 | 9         | 31.03%  |
| Qualcomm Atheros      | 3         | 10.34%  |
| JMicron Technology    | 1         | 3.45%   |
| Google                | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 31.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 17.24%  |
| Intel Ethernet Connection I219-LM                                 | 3         | 10.34%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 3.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 3.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.45%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.45%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.45%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.45%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 3.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 52.46%  |
| Ethernet | 29        | 47.54%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 53.85%  |
| WiFi     | 24        | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 87.5%   |
| 1     | 4         | 12.5%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 93.75%  |
| Yes  | 2         | 6.25%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 47.62%  |
| Qualcomm Atheros Communications | 3         | 14.29%  |
| Broadcom                        | 3         | 14.29%  |
| IMC Networks                    | 2         | 9.52%   |
| Apple                           | 2         | 9.52%   |
| Realtek Semiconductor           | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 8         | 38.1%   |
| Intel AX200 Bluetooth                             | 2         | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 4.76%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1           | 1         | 4.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 4.76%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)   | 1         | 4.76%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS  | 1         | 4.76%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 4.76%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 4.76%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 4.76%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]  | 1         | 4.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 1         | 4.76%   |
| Apple Broadcom Bluetooth 2.1 module               | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 29        | 76.32%  |
| AMD               | 4         | 10.53%  |
| Nvidia            | 3         | 7.89%   |
| Texas Instruments | 1         | 2.63%   |
| GN Netcom         | 1         | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 15.56%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 11.11%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 8.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 4.44%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.44%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 4.44%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.44%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 2.22%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 2.22%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.22%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.22%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.22%   |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 2.22%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 2.22%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 2.22%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 1         | 2.22%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 41.03%  |
| Kingston            | 6         | 15.38%  |
| SK Hynix            | 5         | 12.82%  |
| Unknown             | 2         | 5.13%   |
| Ramaxel Technology  | 2         | 5.13%   |
| Micron Technology   | 2         | 5.13%   |
| Nanya Technology    | 1         | 2.56%   |
| Kingmax             | 1         | 2.56%   |
| Elpida              | 1         | 2.56%   |
| Crucial             | 1         | 2.56%   |
| Corsair             | 1         | 2.56%   |
| A-DATA Technology   | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1334MT/s         | 2         | 4.65%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s         | 2         | 4.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 4.65%   |
| Unknown RAM Module 2GB SODIMM DDR2                       | 1         | 2.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s               | 1         | 2.33%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s             | 1         | 2.33%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 2.33%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 2.33%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 2.33%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 2.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 2.33%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s    | 1         | 2.33%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s    | 1         | 2.33%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2133MT/s    | 1         | 2.33%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s   | 1         | 2.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s    | 1         | 2.33%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s    | 1         | 2.33%   |
| Ramaxel RAM RMT3190ME76F8F1600 2GB SODIMM DDR3 1067MT/s  | 1         | 2.33%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1066MT/s  | 1         | 2.33%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s     | 1         | 2.33%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s     | 1         | 2.33%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Kingston RAM TSB16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s   | 1         | 2.33%   |
| Kingston RAM TSB1066D3S7ELF/2G 2GB SODIMM DDR3 1067MT/s  | 1         | 2.33%   |
| Kingston RAM ASU1333D3S9DR8/2G 2GB SODIMM DDR3 1333MT/s  | 1         | 2.33%   |
| Kingston RAM ACR256X64D3S1066C7 2GB SODIMM DDR3 1067MT/s | 1         | 2.33%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s | 1         | 2.33%   |
| Kingston RAM 99U5594-001.A00LF 2GB SODIMM DDR3 1067MT/s  | 1         | 2.33%   |
| Kingston RAM 9905630-033.A00G 16GB SODIMM DDR4 2133MT/s  | 1         | 2.33%   |
| Kingmax RAM FSFE85F-C8HS9 2GB SODIMM DDR3 1067MT/s       | 1         | 2.33%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Crucial RAM CT8G4SFRA32A.C4FE 8GB SODIMM DDR4 3200MT/s   | 1         | 2.33%   |
| Corsair RAM CMSA8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s  | 1         | 2.33%   |
| A-DATA RAM AM1L16BC8R2-B1QS 8GB SODIMM DDR3 1600MT/s     | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR3 | 21        | 65.63%  |
| DDR4 | 9         | 28.13%  |
| DDR2 | 2         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 32        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 32.43%  |
| 2048  | 12        | 32.43%  |
| 4096  | 9         | 24.32%  |
| 16384 | 2         | 5.41%   |
| 1024  | 2         | 5.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 13        | 35.14%  |
| 1333    | 4         | 10.81%  |
| 2667    | 3         | 8.11%   |
| 2400    | 3         | 8.11%   |
| 2133    | 3         | 8.11%   |
| 1334    | 3         | 8.11%   |
| 1067    | 3         | 8.11%   |
| 3200    | 2         | 5.41%   |
| 1066    | 1         | 2.7%    |
| 667     | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

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
| Chicony Electronics                    | 9         | 32.14%  |
| Lite-On Technology                     | 3         | 10.71%  |
| Quanta                                 | 2         | 7.14%   |
| Lenovo                                 | 2         | 7.14%   |
| Z-Star Microelectronics                | 1         | 3.57%   |
| Suyin                                  | 1         | 3.57%   |
| Sunplus Innovation Technology          | 1         | 3.57%   |
| Realtek Semiconductor                  | 1         | 3.57%   |
| Microdia                               | 1         | 3.57%   |
| Luxvisions Innotech Limited            | 1         | 3.57%   |
| Importek                               | 1         | 3.57%   |
| IMC Networks                           | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| Apple                                  | 1         | 3.57%   |
| Alcor Micro                            | 1         | 3.57%   |
| Acer                                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 7.14%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 3.57%   |
| Suyin Integrated_Webcam_HD                          | 1         | 3.57%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 3.57%   |
| Realtek USB Camera                                  | 1         | 3.57%   |
| Quanta HP Webcam                                    | 1         | 3.57%   |
| Quanta HP TrueVision HD Camera                      | 1         | 3.57%   |
| Microdia Integrated Webcam                          | 1         | 3.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.57%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 3.57%   |
| Lite-On Integrated Camera                           | 1         | 3.57%   |
| Lite-On HP HD Camera                                | 1         | 3.57%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 3.57%   |
| Lenovo Integrated Webcam                            | 1         | 3.57%   |
| Importek TOSHIBA Web Camera                         | 1         | 3.57%   |
| IMC Networks EasyCamera                             | 1         | 3.57%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 3.57%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.57%   |
| Chicony USB 2.0 VGA UVC WebCam                      | 1         | 3.57%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 3.57%   |
| Chicony HD WebCam                                   | 1         | 3.57%   |
| Chicony Chicony USB 2.0 Camera                      | 1         | 3.57%   |
| Chicony 1.3M Webcam                                 | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 3.57%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 3.57%   |
| Alcor Micro Acer Integrated Webcam                  | 1         | 3.57%   |
| Acer ThinkPad P50 Integrated Camera                 | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 50%     |
| Upek                  | 1         | 12.5%   |
| Synaptics             | 1         | 12.5%   |
| STMicroelectronics    | 1         | 12.5%   |
| LighTuning Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI                        | 1         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 12.5%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 12.5%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 12.5%   |

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
| 2     | 10        | 31.25%  |
| 1     | 10        | 31.25%  |
| 4     | 4         | 12.5%   |
| 3     | 4         | 12.5%   |
| 0     | 4         | 12.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 24        | 46.15%  |
| Net/wireless             | 8         | 15.38%  |
| Fingerprint reader       | 8         | 15.38%  |
| Bluetooth                | 6         | 11.54%  |
| Card reader              | 5         | 9.62%   |
| Sound                    | 1         | 1.92%   |

