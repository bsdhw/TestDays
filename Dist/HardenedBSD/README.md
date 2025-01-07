HardenedBSD - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for HardenedBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/HardenedBSD/Desktop/README.md) and [notebooks](/Dist/HardenedBSD/Notebook/README.md).

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

Total: 23

| Vendor     | Model                       | Form-Factor | Probe                                                     | Date         |
|------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Framework  | Laptop 16 (AMD Ryzen 704... | Notebook    | [ebaa050586](https://bsd-hardware.info/?probe=ebaa050586) | Dec 06, 2024 |
| Dell       | Precision M4800             | Notebook    | [437d5c965b](https://bsd-hardware.info/?probe=437d5c965b) | Nov 15, 2024 |
| Dell       | Precision M4800             | Notebook    | [b586c78d26](https://bsd-hardware.info/?probe=b586c78d26) | Nov 15, 2024 |
| Apple      | MacBookPro10,1              | Notebook    | [1a3d253769](https://bsd-hardware.info/?probe=1a3d253769) | Oct 12, 2021 |
| Lenovo     | ThinkPad T410 2518C5U       | Notebook    | [e937639adc](https://bsd-hardware.info/?probe=e937639adc) | Sep 25, 2021 |
| ASUSTek    | F2A85-M                     | Desktop     | [5b7623f03b](https://bsd-hardware.info/?probe=5b7623f03b) | Sep 21, 2021 |
| Dell       | 04F3CJ A03                  | Server      | [d778079c7f](https://bsd-hardware.info/?probe=d778079c7f) | Sep 20, 2021 |
| Protectli  | FW6 Ver                     | Desktop     | [5ef1909125](https://bsd-hardware.info/?probe=5ef1909125) | Aug 30, 2021 |
| Supermicro | X10DRU-i+B                  | Desktop     | [26fd8cd5f0](https://bsd-hardware.info/?probe=26fd8cd5f0) | Jul 06, 2021 |
| Unknown    | Raspberry Pi                | Soc         | [608812bde1](https://bsd-hardware.info/?probe=608812bde1) | Apr 17, 2021 |
| HP         | ProLiant DL120 Gen9         | Server      | [533b1e078e](https://bsd-hardware.info/?probe=533b1e078e) | Mar 17, 2021 |
| Fujitsu    | D3279-H1 S26361-D3279-H1... | Server      | [7a9d95b303](https://bsd-hardware.info/?probe=7a9d95b303) | Mar 17, 2021 |
| Fujitsu    | D3383-A1 S26361-D3383-A1... | Server      | [6e6f1b0f99](https://bsd-hardware.info/?probe=6e6f1b0f99) | Mar 17, 2021 |
| Fujitsu    | D3417-B2 S26361-D3417-B2    | Desktop     | [0e766746c4](https://bsd-hardware.info/?probe=0e766746c4) | Mar 17, 2021 |
| Supermicro | X10SDV-4C-TLN2F             | Server      | [fa0e0228a3](https://bsd-hardware.info/?probe=fa0e0228a3) | Mar 17, 2021 |
| iEi        | E452 V1.00                  | Desktop     | [b5665d0df2](https://bsd-hardware.info/?probe=b5665d0df2) | Mar 17, 2021 |
| Supermicro | X10DRi                      | Server      | [93a8b87e1c](https://bsd-hardware.info/?probe=93a8b87e1c) | Jan 26, 2021 |
| Sony       | VPCCB17FG                   | Notebook    | [a69fa2363e](https://bsd-hardware.info/?probe=a69fa2363e) | Dec 24, 2020 |
| Lenovo     | ThinkPad X240 20AMS0RR00    | Notebook    | [0f9b8d2e3b](https://bsd-hardware.info/?probe=0f9b8d2e3b) | Dec 22, 2020 |
| Dell       | Precision 7550              | Notebook    | [9983a81086](https://bsd-hardware.info/?probe=9983a81086) | Jul 10, 2020 |
| Lenovo     | ThinkPad P51 20HH001RMX     | Notebook    | [81efa4b3d3](https://bsd-hardware.info/?probe=81efa4b3d3) | May 25, 2020 |
| Dell       | Precision 7540              | Notebook    | [aa891d8f27](https://bsd-hardware.info/?probe=aa891d8f27) | May 22, 2020 |
| ASUSTek    | X71SL                       | Notebook    | [ab5297a63d](https://bsd-hardware.info/?probe=ab5297a63d) | May 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| HardenedBSD 13.0-STABLE-HBSD  | 6         | 28.57%  |
| HardenedBSD 12.2--HBSD        | 6         | 28.57%  |
| HardenedBSD 13.0-CURRENT-HBSD | 3         | 14.29%  |
| HardenedBSD 14.2-STABLE-HBSD  | 2         | 9.52%   |
| HardenedBSD 14.0-CURRENT-HBSD | 2         | 9.52%   |
| HardenedBSD 13.0-ALPHA1-HBSD  | 1         | 4.76%   |
| HardenedBSD 12.1--HBSD        | 1         | 4.76%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| HardenedBSD | 21        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 20        | 95.24%  |
| arm64 | 1         | 4.76%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 11        | 52.38%  |
| i3      | 5         | 23.81%  |
| XFCE    | 2         | 9.52%   |
| MATE    | 2         | 9.52%   |
| KDE5    | 1         | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 11        | 52.38%  |
| X11     | 9         | 42.86%  |
| Wayland | 1         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 14        | 66.67%  |
| SLiM    | 4         | 19.05%  |
| SDDM    | 2         | 9.52%   |
| Ly      | 1         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 9         | 42.86%  |
| C       | 8         | 38.1%   |
| en_US   | 3         | 14.29%  |
| fr_FR   | 1         | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 19        | 90.48%  |
| BIOS | 2         | 9.52%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 18        | 85.71%  |
| Ufs  | 3         | 14.29%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 21        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Dell             | 4         | 19.05%  |
| Supermicro       | 3         | 14.29%  |
| Lenovo           | 3         | 14.29%  |
| Fujitsu          | 3         | 14.29%  |
| Sony             | 1         | 4.76%   |
| Protectli        | 1         | 4.76%   |
| iEi              | 1         | 4.76%   |
| Hewlett-Packard  | 1         | 4.76%   |
| Framework        | 1         | 4.76%   |
| ASUSTek Computer | 1         | 4.76%   |
| Apple            | 1         | 4.76%   |
| Unknown          | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Supermicro X10DRi                           | 1         | 4.76%   |
| Supermicro SYS-1028U-TN10RT+                | 1         | 4.76%   |
| Supermicro Super Server                     | 1         | 4.76%   |
| Sony VPCCB17FG                              | 1         | 4.76%   |
| Protectli FW6                               | 1         | 4.76%   |
| Lenovo ThinkPad X240 20AMS0RR00             | 1         | 4.76%   |
| Lenovo ThinkPad T410 2518C5U                | 1         | 4.76%   |
| Lenovo ThinkPad P51 20HH001RMX              | 1         | 4.76%   |
| iEi E452                                    | 1         | 4.76%   |
| HP ProLiant DL120 Gen9                      | 1         | 4.76%   |
| Fujitsu PRIMERGY RX2530 M4                  | 1         | 4.76%   |
| Fujitsu PRIMERGY RX2510 M2                  | 1         | 4.76%   |
| Fujitsu D3417-B2 S26361-D3417-B2            | 1         | 4.76%   |
| Framework Laptop 16 (AMD Ryzen 7040 Series) | 1         | 4.76%   |
| Dell Precision M4800                        | 1         | 4.76%   |
| Dell Precision 7550                         | 1         | 4.76%   |
| Dell Precision 7540                         | 1         | 4.76%   |
| Dell PowerEdge R7515                        | 1         | 4.76%   |
| ASUS F2A85-M                                | 1         | 4.76%   |
| Apple MacBookPro10,1                        | 1         | 4.76%   |
| Unknown                                     | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 3         | 14.29%  |
| Dell Precision               | 3         | 14.29%  |
| Fujitsu PRIMERGY             | 2         | 9.52%   |
| Supermicro X10DRi            | 1         | 4.76%   |
| Supermicro SYS-1028U-TN10RT+ | 1         | 4.76%   |
| Supermicro Super             | 1         | 4.76%   |
| Sony VPCCB17FG               | 1         | 4.76%   |
| Protectli FW6                | 1         | 4.76%   |
| iEi E452                     | 1         | 4.76%   |
| HP ProLiant                  | 1         | 4.76%   |
| Fujitsu D3417-B2             | 1         | 4.76%   |
| Framework Laptop             | 1         | 4.76%   |
| Dell PowerEdge               | 1         | 4.76%   |
| ASUS F2A85-M                 | 1         | 4.76%   |
| Apple MacBookPro10           | 1         | 4.76%   |
| Unknown                      | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 7         | 33.33%  |
| 2017    | 5         | 23.81%  |
| 2015    | 2         | 9.52%   |
| 2013    | 2         | 9.52%   |
| 2024    | 1         | 4.76%   |
| 2014    | 1         | 4.76%   |
| 2011    | 1         | 4.76%   |
| 2010    | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 9         | 42.86%  |
| Server         | 6         | 28.57%  |
| Desktop        | 5         | 23.81%  |
| System on chip | 1         | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 21        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 64.01-256.0     | 6         | 28.57%  |
| 8.01-16.0       | 6         | 28.57%  |
| 32.01-64.0      | 5         | 23.81%  |
| 16.01-24.0      | 3         | 14.29%  |
| More than 256.0 | 1         | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 5         | 23.81%  |
| 4.01-8.0    | 4         | 19.05%  |
| 0.51-1.0    | 3         | 14.29%  |
| 2.01-3.0    | 2         | 9.52%   |
| 1.01-2.0    | 2         | 9.52%   |
| 32.01-64.0  | 1         | 4.76%   |
| 24.01-32.0  | 1         | 4.76%   |
| 64.01-256.0 | 1         | 4.76%   |
| 16.01-24.0  | 1         | 4.76%   |
| 8.01-16.0   | 1         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 9         | 42.86%  |
| 0      | 3         | 14.29%  |
| 5      | 2         | 9.52%   |
| 3      | 2         | 9.52%   |
| 2      | 2         | 9.52%   |
| 14     | 1         | 4.76%   |
| 12     | 1         | 4.76%   |
| 4      | 1         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 17        | 80.95%  |
| Yes       | 4         | 19.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 12        | 57.14%  |
| Yes       | 9         | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 12        | 57.14%  |
| Yes       | 9         | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 47.62%  |
| Netherlands | 4         | 19.05%  |
| Germany     | 2         | 9.52%   |
| France      | 2         | 9.52%   |
| Moldova     | 1         | 4.76%   |
| Hong Kong   | 1         | 4.76%   |
| Finland     | 1         | 4.76%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Vienna         | 5         | 23.81%  |
| Columbia       | 2         | 9.52%   |
| Vauclerc       | 1         | 4.76%   |
| Seattle        | 1         | 4.76%   |
| San Francisco  | 1         | 4.76%   |
| RГ®bniЕЈa  | 1         | 4.76%   |
| Nanterre       | 1         | 4.76%   |
| Naaldwijk      | 1         | 4.76%   |
| Falkenstein    | 1         | 4.76%   |
| Espoo          | 1         | 4.76%   |
| Eindhoven      | 1         | 4.76%   |
| Denver         | 1         | 4.76%   |
| Cheung Sha Wan | 1         | 4.76%   |
| Beekbergen     | 1         | 4.76%   |
| Barneveld      | 1         | 4.76%   |
| Ahrensburg     | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 6      | 11.11%  |
| Samsung Electronics | 3         | 7      | 11.11%  |
| Hewlett-Packard     | 3         | 22     | 11.11%  |
| Seagate             | 2         | 3      | 7.41%   |
| SATADOM             | 2         | 4      | 7.41%   |
| Lenovo              | 2         | 4      | 7.41%   |
| UDinfo              | 1         | 1      | 3.7%    |
| Toshiba             | 1         | 1      | 3.7%    |
| SPCC                | 1         | 1      | 3.7%    |
| Protectli           | 1         | 1      | 3.7%    |
| Phison              | 1         | 1      | 3.7%    |
| Patriot             | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 2      | 3.7%    |
| Kingston            | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |
| Crucial             | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| SATADOM SL 3IE3 V2 64GB                 | 2         | 6.45%   |
| Lenovo WD2004FBYZ-23YC 03X3795 2TB      | 2         | 6.45%   |
| HP SSD EX950 512GB                      | 2         | 6.45%   |
| WDC WD80EFAX-68KNBN0 8TB                | 1         | 3.23%   |
| WDC WD60EFRX-68L0BN1 6TB                | 1         | 3.23%   |
| WDC WD40EFRX-68WT0N0 4TB                | 1         | 3.23%   |
| WDC WD10EAVS-00D7B0 1TB                 | 1         | 3.23%   |
| UDinfo M2S 120GB                        | 1         | 3.23%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB | 1         | 3.23%   |
| SPCC Solid State Disk 128GB             | 1         | 3.23%   |
| Seagate XF1230-1A0480 480GB             | 1         | 3.23%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 3.23%   |
| Samsung SSD 960 EVO 250GB               | 1         | 3.23%   |
| Samsung SSD 860 EVO M.2 250GB           | 1         | 3.23%   |
| Samsung HD503HI 500GB                   | 1         | 3.23%   |
| Samsung HD501LJ 500GB                   | 1         | 3.23%   |
| Samsung HD322GJ 320GB                   | 1         | 3.23%   |
| Samsung HD256GJ 250GB                   | 1         | 3.23%   |
| Protectli 64GB mSATA                    | 1         | 3.23%   |
| Phison SATA SSD 1TB                     | 1         | 3.23%   |
| Patriot P210 512GB                      | 1         | 3.23%   |
| Micron 5200_MTFDDAK1T9TDN 1.9TB         | 1         | 3.23%   |
| Kingston SKC1000240G 240GB              | 1         | 3.23%   |
| Intel SSDPE21D280GA 280GB               | 1         | 3.23%   |
| HGST HTS725050A7E630 500GB              | 1         | 3.23%   |
| HP MB3000FBNWV 3TB                      | 1         | 3.23%   |
| Crucial CT240BX500SSD1 240GB            | 1         | 3.23%   |
| Apple SSD SD512E 500GB                  | 1         | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 6      | 33.33%  |
| Lenovo              | 2         | 4      | 22.22%  |
| Seagate             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 4      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |
| Hewlett-Packard     | 1         | 4      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SATADOM             | 2         | 4      | 16.67%  |
| UDinfo              | 1         | 1      | 8.33%   |
| SPCC                | 1         | 1      | 8.33%   |
| Seagate             | 1         | 2      | 8.33%   |
| Samsung Electronics | 1         | 2      | 8.33%   |
| Protectli           | 1         | 1      | 8.33%   |
| Phison              | 1         | 1      | 8.33%   |
| Patriot             | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 2      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |
| Apple               | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 10        | 17     | 43.48%  |
| HDD  | 7         | 20     | 30.43%  |
| NVMe | 6         | 22     | 26.09%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 37     | 72.73%  |
| NVMe | 6         | 22     | 27.27%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 18     | 47.62%  |
| 1.01-2.0   | 4         | 7      | 19.05%  |
| 0.51-1.0   | 3         | 3      | 14.29%  |
| 4.01-10.0  | 2         | 3      | 9.52%   |
| 3.01-4.0   | 1         | 2      | 4.76%   |
| 2.01-3.0   | 1         | 4      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 8         | 38.1%   |
| 1001-2000      | 4         | 19.05%  |
| 251-500        | 3         | 14.29%  |
| 51-100         | 2         | 9.52%   |
| More than 3000 | 1         | 4.76%   |
| 21-50          | 1         | 4.76%   |
| 1-20           | 1         | 4.76%   |
| 501-1000       | 1         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 18        | 85.71%  |
| 21-50   | 3         | 14.29%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD10EAVS-00D7B0 1TB           | 1         | 1      | 25%     |
| Samsung Electronics HD501LJ 500GB | 1         | 1      | 25%     |
| Samsung Electronics HD322GJ 320GB | 1         | 1      | 25%     |
| Samsung Electronics HD256GJ 250GB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 3      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 3      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 17        | 50     | 85%     |
| Detected | 1         | 4      | 5%      |
| Malfunc  | 1         | 4      | 5%      |
| Failed   | 1         | 1      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 15        | 48.39%  |
| AMD                      | 3         | 9.68%   |
| Silicon Motion           | 2         | 6.45%   |
| Samsung Electronics      | 2         | 6.45%   |
| Toshiba                  | 1         | 3.23%   |
| SK hynix                 | 1         | 3.23%   |
| Sandisk                  | 1         | 3.23%   |
| Phison Electronics       | 1         | 3.23%   |
| Marvell Technology Group | 1         | 3.23%   |
| Hewlett-Packard          | 1         | 3.23%   |
| Broadcom / LSI           | 1         | 3.23%   |
| Biwin Storage Technology | 1         | 3.23%   |
| ASMedia Technology       | 1         | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3         | 8.11%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3         | 8.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 8.11%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 5.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 5.41%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 2.7%    |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 2.7%    |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 2.7%    |
| Sandisk WD Black SN770M NVMe SSD (DRAM-less)                                   | 1         | 2.7%    |
| Phison E7 NVMe Controller                                                      | 1         | 2.7%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.7%    |
| Intel Optane SSD 900P Series                                                   | 1         | 2.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.7%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1         | 2.7%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1         | 2.7%    |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1         | 2.7%    |
| Intel C610/X99 series chipset SATA Controller [RAID mode]                      | 1         | 2.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.7%    |
| HP Smart Array Gen9 Controllers                                                | 1         | 2.7%    |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 1         | 2.7%    |
| Biwin Storage EX950 NVMe SSD                                                   | 1         | 2.7%    |
| ASMedia 106x SATA/RAID Controller                                              | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 15        | 53.57%  |
| NVMe | 9         | 32.14%  |
| RAID | 3         | 10.71%  |
| SAS  | 1         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 16        | 76.19%  |
| AMD    | 4         | 19.05%  |
| ARM    | 1         | 4.76%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Xeon W-10885M CPU @ 2.40GHz          | 1         | 4.76%   |
| Intel Xeon Silver 4108 CPU @ 1.80GHz       | 1         | 4.76%   |
| Intel Xeon E-2286M CPU @ 2.40GHz           | 1         | 4.76%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz        | 1         | 4.76%   |
| Intel Xeon CPU E5-2650L v3 @ 1.80GHz       | 1         | 4.76%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz        | 1         | 4.76%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz        | 1         | 4.76%   |
| Intel Xeon CPU E3-1275 v5 @ 3.60GHz        | 1         | 4.76%   |
| Intel Xeon CPU D-1521 @ 2.40GHz            | 1         | 4.76%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz         | 1         | 4.76%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz         | 1         | 4.76%   |
| Intel Core i7-3720QM CPU @ 2.60GHz         | 1         | 4.76%   |
| Intel Core i7-2620M CPU @ 2.70GHz          | 1         | 4.76%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 1         | 4.76%   |
| Intel Core i5 CPU M 540 @ 2.53GHz          | 1         | 4.76%   |
| Intel Core i3-7100U CPU @ 2.40GHz          | 1         | 4.76%   |
| ARM Cortex-A57 r1p2                        | 1         | 4.76%   |
| AMD Ryzen 9 7940HS w/ Radeon 780M Graphics | 1         | 4.76%   |
| AMD GX-424CC SOC with Radeon R5E Graphics  | 1         | 4.76%   |
| AMD EPYC 7402P 24-Core Processor           | 1         | 4.76%   |
| AMD A8-6600K APU with Radeon HD Graphics   | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Xeon        | 8         | 38.1%   |
| Intel Core i7     | 4         | 19.05%  |
| Intel Core i5     | 2         | 9.52%   |
| Intel Xeon Silver | 1         | 4.76%   |
| Intel Core i3     | 1         | 4.76%   |
| ARM Cortex        | 1         | 4.76%   |
| AMD Ryzen 9       | 1         | 4.76%   |
| AMD GX            | 1         | 4.76%   |
| AMD EPYC          | 1         | 4.76%   |
| AMD A8            | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 7         | 33.33%  |
| 8       | 6         | 28.57%  |
| 2       | 4         | 19.05%  |
| 48      | 1         | 4.76%   |
| 14      | 1         | 4.76%   |
| 12      | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 20        | 95.24%  |
| Unknown | 1         | 4.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 16        | 76.19%  |
| 1       | 4         | 19.05%  |
| Unknown | 1         | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Haswell     | 5         | 23.81%  |
| KabyLake    | 3         | 14.29%  |
| Skylake     | 2         | 9.52%   |
| Broadwell   | 2         | 9.52%   |
| Unknown     | 2         | 9.52%   |
| Zen 2       | 1         | 4.76%   |
| Westmere    | 1         | 4.76%   |
| SandyBridge | 1         | 4.76%   |
| Puma        | 1         | 4.76%   |
| Piledriver  | 1         | 4.76%   |
| IvyBridge   | 1         | 4.76%   |
| CometLake   | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 6         | 26.09%  |
| Intel                      | 6         | 26.09%  |
| Matrox Electronics Systems | 4         | 17.39%  |
| AMD                        | 4         | 17.39%  |
| ASPEED Technology          | 3         | 13.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                  | 3         | 13.04%  |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)         | 2         | 8.7%    |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 1         | 4.35%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 4.35%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                     | 1         | 4.35%   |
| Nvidia GM204GL [Quadro M4000]                                             | 1         | 4.35%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 4.35%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 4.35%   |
| Matrox Electronics Systems MGA G200EH                                     | 1         | 4.35%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller  | 1         | 4.35%   |
| Intel HD Graphics P530                                                    | 1         | 4.35%   |
| Intel HD Graphics 620                                                     | 1         | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 4.35%   |
| Intel Coffee Lake-S GT2 [UHD Graphics P630]                               | 1         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 4.35%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 1         | 4.35%   |
| AMD Turks XT [Radeon HD 6670/7670]                                        | 1         | 4.35%   |
| AMD Phoenix1                                                              | 1         | 4.35%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 1         | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Nvidia      | 4         | 19.05%  |
| 1 x Matrox      | 4         | 19.05%  |
| 1 x Intel       | 4         | 19.05%  |
| 1 x AMD         | 3         | 14.29%  |
| 1 x ASPEED      | 2         | 9.52%   |
| Other           | 1         | 4.76%   |
| Nvidia + ASPEED | 1         | 4.76%   |
| Intel + Nvidia  | 1         | 4.76%   |
| Intel + AMD     | 1         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 15        | 71.43%  |
| Proprietary | 5         | 23.81%  |
| Unknown     | 1         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 66.67%  |
| 1.01-2.0   | 2         | 9.52%   |
| 7.01-8.0   | 1         | 4.76%   |
| 5.01-6.0   | 1         | 4.76%   |
| 3.01-4.0   | 1         | 4.76%   |
| 0.51-1.0   | 1         | 4.76%   |
| 0.01-0.5   | 1         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 3         | 25%     |
| Samsung Electronics  | 2         | 16.67%  |
| Lenovo               | 2         | 16.67%  |
| AU Optronics         | 2         | 16.67%  |
| Ancor Communications | 2         | 16.67%  |
| Sharp                | 1         | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 600x340mm 27.2-inch | 2         | 16.67%  |
| Sharp LCD Monitor SHP13F9 3200x1800 350x190mm 15.7-inch               | 1         | 8.33%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch     | 1         | 8.33%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch  | 1         | 8.33%   |
| Lenovo P24q-10 LEN61A5 2560x1440 530x300mm 24.0-inch                  | 1         | 8.33%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 1         | 8.33%   |
| BOE LCD Monitor BOE0BC9 2560x1600 340x220mm 15.9-inch                 | 1         | 8.33%   |
| BOE LCD Monitor BOE0819 1920x1080 340x190mm 15.3-inch                 | 1         | 8.33%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 1         | 8.33%   |
| AU Optronics LCD Monitor AUO24ED 1920x1080 340x190mm 15.3-inch        | 1         | 8.33%   |
| AU Optronics LCD Monitor 3840x2160                                    | 1         | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 2560x1440 (QHD)    | 3         | 25%     |
| 3840x2160 (4K)     | 2         | 16.67%  |
| 1920x1080 (FHD)    | 2         | 16.67%  |
| 3200x1800 (QHD+)   | 1         | 8.33%   |
| 2560x1600          | 1         | 8.33%   |
| 1680x1050 (WSXGA+) | 1         | 8.33%   |
| 1440x900 (WXGA+)   | 1         | 8.33%   |
| 1366x768 (WXGA)    | 1         | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4         | 33.33%  |
| 27      | 2         | 16.67%  |
| 31      | 1         | 8.33%   |
| 24      | 1         | 8.33%   |
| 22      | 1         | 8.33%   |
| 14      | 1         | 8.33%   |
| 12      | 1         | 8.33%   |
| Unknown | 1         | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 4         | 33.33%  |
| 501-600     | 3         | 25%     |
| 201-300     | 2         | 16.67%  |
| 601-700     | 1         | 8.33%   |
| 401-500     | 1         | 8.33%   |
| Unknown     | 1         | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5         | 55.56%  |
| 16/10   | 2         | 22.22%  |
| 3/2     | 1         | 11.11%  |
| Unknown | 1         | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2         | 16.67%  |
| 201-250        | 2         | 16.67%  |
| 91-100         | 2         | 16.67%  |
| 81-90          | 1         | 8.33%   |
| 61-70          | 1         | 8.33%   |
| 351-500        | 1         | 8.33%   |
| 111-120        | 1         | 8.33%   |
| 101-110        | 1         | 8.33%   |
| Unknown        | 1         | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 5         | 45.45%  |
| 161-240 | 2         | 18.18%  |
| 101-120 | 2         | 18.18%  |
| 51-100  | 1         | 9.09%   |
| Unknown | 1         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 12        | 57.14%  |
| 1     | 5         | 23.81%  |
| 2     | 4         | 19.05%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 16        | 59.26%  |
| Qualcomm Atheros                  | 4         | 14.81%  |
| Realtek Semiconductor             | 2         | 7.41%   |
| Broadcom                          | 2         | 7.41%   |
| Mellanox Technologies             | 1         | 3.7%    |
| Marvell Technology Group          | 1         | 3.7%    |
| Ericsson Business Mobile Networks | 1         | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel I350 Gigabit Network Connection                                          | 4         | 12.12%  |
| Intel I210 Gigabit Network Connection                                          | 2         | 6.06%   |
| Realtek USB 2.5GbE Controller                                                  | 1         | 3.03%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1         | 3.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 3.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 3.03%   |
| Mellanox MT27700 Family [ConnectX-4]                                           | 1         | 3.03%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 3.03%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 3.03%   |
| Intel Wireless 7260                                                            | 1         | 3.03%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 1         | 3.03%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1         | 3.03%   |
| Intel Ethernet Connection X722 for 1GbE                                        | 1         | 3.03%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 1         | 3.03%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 3.03%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 3.03%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 3.03%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 3.03%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 3.03%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 1         | 3.03%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 3.03%   |
| Ericsson Business Mobile Networks N5321 gw Mobile Broadband Serial Port III    | 1         | 3.03%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 3.03%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 1         | 3.03%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 1         | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Qualcomm Atheros | 4         | 44.44%  |
| Intel            | 4         | 44.44%  |
| Broadcom         | 1         | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 11.11%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 11.11%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 11.11%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 11.11%  |
| Intel Wireless 8265 / 8275                                     | 1         | 11.11%  |
| Intel Wireless 7260                                            | 1         | 11.11%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 11.11%  |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 11.11%  |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 15        | 71.43%  |
| Realtek Semiconductor    | 2         | 9.52%   |
| Broadcom                 | 2         | 9.52%   |
| Qualcomm Atheros         | 1         | 4.76%   |
| Marvell Technology Group | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel I350 Gigabit Network Connection                                          | 4         | 18.18%  |
| Intel I210 Gigabit Network Connection                                          | 2         | 9.09%   |
| Realtek USB 2.5GbE Controller                                                  | 1         | 4.55%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1         | 4.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 4.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 4.55%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1         | 4.55%   |
| Intel Ethernet Connection X722 for 1GbE                                        | 1         | 4.55%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 1         | 4.55%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 4.55%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 4.55%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 4.55%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 4.55%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 4.55%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 4.55%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 4.55%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 4.55%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 21        | 65.63%  |
| WiFi     | 9         | 28.13%  |
| Modem    | 1         | 3.13%   |
| Unknown  | 1         | 3.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 19        | 73.08%  |
| WiFi     | 6         | 23.08%  |
| Modem    | 1         | 3.85%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 14        | 66.67%  |
| 1     | 4         | 19.05%  |
| 6     | 1         | 4.76%   |
| 5     | 1         | 4.76%   |
| 4     | 1         | 4.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 14        | 66.67%  |
| Yes  | 7         | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3         | 33.33%  |
| Qualcomm Atheros Communications | 2         | 22.22%  |
| Foxconn / Hon Hai               | 1         | 11.11%  |
| Cambridge Silicon Radio         | 1         | 11.11%  |
| Broadcom                        | 1         | 11.11%  |
| Apple                           | 1         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE                                 | 1         | 11.11%  |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device                                | 1         | 11.11%  |
| Intel Bluetooth wireless interface                                                  | 1         | 11.11%  |
| Intel AX210 Bluetooth                                                               | 1         | 11.11%  |
| Intel AX201 Bluetooth                                                               | 1         | 11.11%  |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 11.11%  |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 11.11%  |
| Apple Bluetooth Host Controller                                                     | 1         | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 9         | 52.94%  |
| Nvidia | 5         | 29.41%  |
| AMD    | 3         | 17.65%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD FCH Azalia Controller                                                  | 2         | 9.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 4.76%   |
| Nvidia High Definition Audio Controller                                    | 1         | 4.76%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 4.76%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 4.76%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 4.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 4.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 4.76%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 4.76%   |
| Intel CM238 HD Audio Controller                                            | 1         | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 4.76%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 4.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 4.76%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 4.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 4.76%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 1         | 4.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 31.82%  |
| SK hynix            | 4         | 18.18%  |
| Kingston            | 4         | 18.18%  |
| Micron Technology   | 2         | 9.09%   |
| Unknown             | 1         | 4.55%   |
| Hewlett-Packard     | 1         | 4.55%   |
| G.Skill             | 1         | 4.55%   |
| Corsair             | 1         | 4.55%   |
| A-DATA Technology   | 1         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s   | 2         | 9.09%   |
| Unknown RAM Module 4GB SODIMM DDR3                     | 1         | 4.55%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s           | 1         | 4.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s | 1         | 4.55%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1         | 4.55%   |
| SK hynix RAM HMA41GR7BJR4N-VK 8GB DIMM DDR4 2666MT/s   | 1         | 4.55%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s | 1         | 4.55%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s  | 1         | 4.55%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 1         | 4.55%   |
| Samsung RAM M393A2K43CB2-CTD 16GB DIMM DDR4 2667MT/s   | 1         | 4.55%   |
| Samsung RAM M391A2K43BB1-CPB 16GB DIMM DDR4 2133MT/s   | 1         | 4.55%   |
| Micron RAM 18ASF2G72HZ-2G6E1 16GB SODIMM DDR4 2667MT/s | 1         | 4.55%   |
| Micron RAM 18ASF1G72PZ-2G6F1 8GB DIMM DDR4 2666MT/s    | 1         | 4.55%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s  | 1         | 4.55%   |
| Kingston RAM HP16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s  | 1         | 4.55%   |
| Kingston RAM 9965669-031.A00G 16GB DIMM DDR4 2400MT/s  | 1         | 4.55%   |
| Kingston RAM 9905711-038.A00G 8GB SODIMM DDR4 2667MT/s | 1         | 4.55%   |
| HP RAM 752368-081 8GB DIMM DDR4 2133MT/s               | 1         | 4.55%   |
| G.Skill RAM F3-10666CL9-4GBSQ 4GB SODIMM DDR3 1334MT/s | 1         | 4.55%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s    | 1         | 4.55%   |
| A-DATA RAM AD5S560048G-B 48GB SODIMM DDR5 5600MT/s     | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 12        | 60%     |
| DDR3 | 7         | 35%     |
| DDR5 | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 11        | 55%     |
| DIMM   | 9         | 45%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 9         | 45%     |
| 16384 | 4         | 20%     |
| 32768 | 3         | 15%     |
| 4096  | 3         | 15%     |
| 49152 | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 5         | 23.81%  |
| 2133    | 4         | 19.05%  |
| 1600    | 4         | 19.05%  |
| 2400    | 3         | 14.29%  |
| 5600    | 1         | 4.76%   |
| 2666    | 1         | 4.76%   |
| 1334    | 1         | 4.76%   |
| 1333    | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

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


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Ricoh                 | 1         | 16.67%  |
| Realtek Semiconductor | 1         | 16.67%  |
| Microdia              | 1         | 16.67%  |
| Lenovo                | 1         | 16.67%  |
| Bison Electronics     | 1         | 16.67%  |
| Apple                 | 1         | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Ricoh USB2.0 Camera                    | 1         | 16.67%  |
| Realtek Integrated_Webcam_HD           | 1         | 16.67%  |
| Microdia Integrated Webcam             | 1         | 16.67%  |
| Lenovo Integrated Webcam [R5U877]      | 1         | 16.67%  |
| Bison SunplusIT INC. Integrated Camera | 1         | 16.67%  |
| Apple FaceTime HD Camera (Built-in)    | 1         | 16.67%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Upek             | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 50%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 50%     |

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
| 2     | 7         | 33.33%  |
| 0     | 5         | 23.81%  |
| 3     | 4         | 19.05%  |
| 1     | 4         | 19.05%  |
| 5     | 1         | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 14        | 51.85%  |
| Card reader              | 4         | 14.81%  |
| Bluetooth                | 3         | 11.11%  |
| Net/wireless             | 2         | 7.41%   |
| Fingerprint reader       | 2         | 7.41%   |
| Net/ethernet             | 1         | 3.7%    |
| Firewire controller      | 1         | 3.7%    |

