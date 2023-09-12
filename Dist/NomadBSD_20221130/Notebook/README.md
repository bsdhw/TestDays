NomadBSD 20221130 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for NomadBSD 20221130.

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

Total: 23

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| Unknown       | Unknown                     | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| Lenovo        | ThinkPad X230 2325IB1       | [41fbf7d1ca](https://bsd-hardware.info/?probe=41fbf7d1ca) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | [7a5d32eb7f](https://bsd-hardware.info/?probe=7a5d32eb7f) | Jul 29, 2023 |
| HP            | EliteBook 750 G1            | [e0af4797d4](https://bsd-hardware.info/?probe=e0af4797d4) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Dell          | Latitude 7300               | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Acer          | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Intel         | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Acer          | Aspire 7738                 | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| Lenovo        | G50-70 20351                | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple         | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 18        | 94.74%  |
| i386  | 1         | 5.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 11        | 57.89%  |
| xinitrc | 6         | 31.58%  |
| KDE5    | 2         | 10.53%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 19        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 19        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 5         | 26.32%  |
| en_GB   | 5         | 26.32%  |
| fr_FR   | 4         | 21.05%  |
| fi_FI   | 2         | 10.53%  |
| ru_RU   | 1         | 5.26%   |
| lt_LT   | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 19        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 13        | 68.42%  |
| Zfs  | 6         | 31.58%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 12        | 63.16%  |
| MBR  | 7         | 36.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 52.63%  |
| Acer                | 2         | 10.53%  |
| Samsung Electronics | 1         | 5.26%   |
| Hewlett-Packard     | 1         | 5.26%   |
| Fujitsu Siemens     | 1         | 5.26%   |
| Fujitsu             | 1         | 5.26%   |
| Dell                | 1         | 5.26%   |
| Chuwi               | 1         | 5.26%   |
| Apple               | 1         | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung N150/N210/N220                   | 1         | 5.26%   |
| Lenovo Yoga 710-11IKB 80V6               | 1         | 5.26%   |
| Lenovo ThinkPad X280 20KESB4T00          | 1         | 5.26%   |
| Lenovo ThinkPad X230 2325IB1             | 1         | 5.26%   |
| Lenovo ThinkPad X230 23255NG             | 1         | 5.26%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT | 1         | 5.26%   |
| Lenovo ThinkPad W520 42844DG             | 1         | 5.26%   |
| Lenovo ThinkPad T470 20HES0EV0A          | 1         | 5.26%   |
| Lenovo ThinkPad E495 20NE000BSP          | 1         | 5.26%   |
| Lenovo ThinkPad E14 20RA0036RT           | 1         | 5.26%   |
| Lenovo G50-70 20351                      | 1         | 5.26%   |
| HP EliteBook 750 G1                      | 1         | 5.26%   |
| Fujitsu Siemens AMILO Li3710             | 1         | 5.26%   |
| Fujitsu CELSIUS H730                     | 1         | 5.26%   |
| Dell Latitude 7300                       | 1         | 5.26%   |
| Chuwi CoreBook X                         | 1         | 5.26%   |
| Apple MacBookPro14,1                     | 1         | 5.26%   |
| Acer Swift SF314-56                      | 1         | 5.26%   |
| Acer Aspire 7738                         | 1         | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 8         | 42.11%  |
| Samsung N150          | 1         | 5.26%   |
| Lenovo Yoga           | 1         | 5.26%   |
| Lenovo G50-70         | 1         | 5.26%   |
| HP EliteBook          | 1         | 5.26%   |
| Fujitsu Siemens AMILO | 1         | 5.26%   |
| Fujitsu CELSIUS       | 1         | 5.26%   |
| Dell Latitude         | 1         | 5.26%   |
| Chuwi CoreBook        | 1         | 5.26%   |
| Apple MacBookPro14    | 1         | 5.26%   |
| Acer Swift            | 1         | 5.26%   |
| Acer Aspire           | 1         | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 3         | 15.79%  |
| 2012 | 3         | 15.79%  |
| 2022 | 2         | 10.53%  |
| 2020 | 2         | 10.53%  |
| 2009 | 2         | 10.53%  |
| 2023 | 1         | 5.26%   |
| 2021 | 1         | 5.26%   |
| 2018 | 1         | 5.26%   |
| 2016 | 1         | 5.26%   |
| 2015 | 1         | 5.26%   |
| 2014 | 1         | 5.26%   |
| 2010 | 1         | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 19        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 94.74%  |
| Yes  | 1         | 5.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 9         | 47.37%  |
| 16.01-24.0 | 5         | 26.32%  |
| 2.01-3.0   | 2         | 10.53%  |
| 4.01-8.0   | 1         | 5.26%   |
| 32.01-64.0 | 1         | 5.26%   |
| 24.01-32.0 | 1         | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 10        | 52.63%  |
| 0.51-1.0 | 6         | 31.58%  |
| 1.01-2.0 | 2         | 10.53%  |
| 2.01-3.0 | 1         | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 73.68%  |
| 2      | 3         | 15.79%  |
| 0      | 2         | 10.53%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 78.95%  |
| Yes       | 4         | 21.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 73.68%  |
| No        | 5         | 26.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 68.42%  |
| No        | 6         | 31.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| UK         | 5         | 26.32%  |
| France     | 5         | 26.32%  |
| USA        | 2         | 10.53%  |
| Russia     | 2         | 10.53%  |
| Finland    | 2         | 10.53%  |
| Spain      | 1         | 5.26%   |
| San Marino | 1         | 5.26%   |
| Lithuania  | 1         | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Moscow         | 2         | 10.53%  |
| Melun          | 2         | 10.53%  |
| West Bromwich  | 1         | 5.26%   |
| Wakefield      | 1         | 5.26%   |
| Vilnius        | 1         | 5.26%   |
| Vaasa          | 1         | 5.26%   |
| Urcuit         | 1         | 5.26%   |
| Turku          | 1         | 5.26%   |
| Seattle        | 1         | 5.26%   |
| Sartrouville   | 1         | 5.26%   |
| San Marino     | 1         | 5.26%   |
| Saint-Raphaël | 1         | 5.26%   |
| Rubí          | 1         | 5.26%   |
| Portland       | 1         | 5.26%   |
| Lincoln        | 1         | 5.26%   |
| Belfast        | 1         | 5.26%   |
| Addlestone     | 1         | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 15%     |
| Samsung Electronics | 3         | 3      | 15%     |
| Crucial             | 2         | 2      | 10%     |
| WDC                 | 1         | 1      | 5%      |
| UMIS                | 1         | 1      | 5%      |
| Toshiba             | 1         | 1      | 5%      |
| SPCC                | 1         | 1      | 5%      |
| SK hynix            | 1         | 1      | 5%      |
| Seagate             | 1         | 1      | 5%      |
| Phison              | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| Hitachi             | 1         | 2      | 5%      |
| AirDisk             | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 5%      |
| UMIS RPJTJ256MED1OWX 256GB        | 1         | 5%      |
| Toshiba KBG40ZNT512G MEMORY 512GB | 1         | 5%      |
| SPCC Solid State Disk 128GB       | 1         | 5%      |
| SK hynix HFM512GDHTNG-8710B 512GB | 1         | 5%      |
| Seagate ST9160314AS 160GB         | 1         | 5%      |
| SanDisk X400 M.2 2280 256GB       | 1         | 5%      |
| SanDisk SDSSDA240G 240GB          | 1         | 5%      |
| SanDisk pSSD 256GB                | 1         | 5%      |
| Samsung SSD PM851 2.5 7mm 256GB   | 1         | 5%      |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 5%      |
| Samsung SSD 850 EVO 2TB           | 1         | 5%      |
| Phison Sabrent Rocket nano 512GB  | 1         | 5%      |
| Kingston SA400S37240G 240GB       | 1         | 5%      |
| Intel SSDPEKKF256G8L 256GB        | 1         | 5%      |
| Hitachi HTS545050B9A300 500GB     | 1         | 5%      |
| Crucial CT256MX100SSD1 256GB      | 1         | 5%      |
| Crucial CT2000BX500SSD1 2TB       | 1         | 5%      |
| AirDisk 512GB SSD                 | 1         | 5%      |
| A-DATA SSD DP900 512GB-DL3        | 1         | 5%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 2      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 27.27%  |
| Samsung Electronics | 3         | 3      | 27.27%  |
| Crucial             | 2         | 2      | 18.18%  |
| SPCC                | 1         | 1      | 9.09%   |
| Kingston            | 1         | 1      | 9.09%   |
| A-DATA Technology   | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 11        | 11     | 55%     |
| NVMe | 6         | 6      | 30%     |
| HDD  | 3         | 4      | 15%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 15     | 68.42%  |
| NVMe | 6         | 6      | 31.58%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 11     | 71.43%  |
| 1.01-2.0   | 2         | 2      | 14.29%  |
| 0.51-1.0   | 2         | 2      | 14.29%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 12        | 63.16%  |
| 21-50      | 3         | 15.79%  |
| 101-250    | 2         | 10.53%  |
| 251-500    | 1         | 5.26%   |
| 501-1000   | 1         | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 19        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545050B9A300 500GB | 1         | 2      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 2      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model              | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 256GB | 1         | 1      | 100%    |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 17        | 18     | 89.47%  |
| Malfunc | 1         | 2      | 5.26%   |
| Failed  | 1         | 1      | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 16        | 76.19%  |
| SK hynix                                | 1         | 4.76%   |
| Shenzhen Unionmemory Information System | 1         | 4.76%   |
| Phison Electronics                      | 1         | 4.76%   |
| MAXIO Technology (Hangzhou)             | 1         | 4.76%   |
| KIOXIA                                  | 1         | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 14.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 9.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 9.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 9.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 9.52%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 4.76%   |
| Shenzhen Unionmemory Information System AM611 PCIe 3.0 NVMe SSD 256GB          | 1         | 4.76%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 4.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 4.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 4.76%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 4.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 4.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 4.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 13        | 61.9%   |
| NVMe | 6         | 28.57%  |
| RAID | 2         | 9.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 94.74%  |
| AMD    | 1         | 5.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel CPU Version                             | 1         | 5.26%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 5.26%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 5.26%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 5.26%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 5.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 5.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 5.26%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 5.26%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 5.26%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 5.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 5.26%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 5.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 5.26%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 5.26%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 5.26%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 1         | 5.26%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 5.26%   |
| Intel 11th Gen Core i5-1130G7 @ 1.10GHz       | 1         | 5.26%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 42.11%  |
| Intel Core i7           | 4         | 21.05%  |
| Other                   | 3         | 15.79%  |
| Intel Core i3           | 1         | 5.26%   |
| Intel Celeron Dual-Core | 1         | 5.26%   |
| Intel Atom              | 1         | 5.26%   |
| AMD Ryzen 7             | 1         | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 9         | 47.37%  |
| 4       | 7         | 36.84%  |
| 12      | 1         | 5.26%   |
| 8       | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 18        | 94.74%  |
| Unknown | 1         | 5.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 14        | 73.68%  |
| 1       | 4         | 21.05%  |
| Unknown | 1         | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 36.84%  |
| Haswell     | 3         | 15.79%  |
| Penryn      | 2         | 10.53%  |
| IvyBridge   | 2         | 10.53%  |
| Zen+        | 1         | 5.26%   |
| TigerLake   | 1         | 5.26%   |
| SandyBridge | 1         | 5.26%   |
| Bonnell     | 1         | 5.26%   |
| Unknown     | 1         | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 81.82%  |
| Nvidia | 3         | 13.64%  |
| AMD    | 1         | 4.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 13.64%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 9.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 9.09%   |
| Nvidia GT216M [GeForce GT 240M]                                           | 1         | 4.55%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 4.55%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 4.55%   |
| Intel UHD Graphics 620                                                    | 1         | 4.55%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                               | 1         | 4.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 4.55%   |
| Intel Iris Plus Graphics 640                                              | 1         | 4.55%   |
| Intel HD Graphics 620                                                     | 1         | 4.55%   |
| Intel HD Graphics 615                                                     | 1         | 4.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 4.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 4.55%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 1         | 4.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 4.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 68.42%  |
| 2 x Intel      | 2         | 10.53%  |
| Intel + Nvidia | 2         | 10.53%  |
| 1 x Nvidia     | 1         | 5.26%   |
| 1 x AMD        | 1         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 18        | 94.74%  |
| Proprietary | 1         | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 25%     |
| Chimei Innolux      | 2         | 25%     |
| LG Display          | 1         | 12.5%   |
| BOE                 | 1         | 12.5%   |
| AU Optronics        | 1         | 12.5%   |
| Apple               | 1         | 12.5%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch | 1         | 12.5%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 12.5%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch          | 1         | 12.5%   |
| Chimei Innolux LCD Monitor CMN1301 2160x1350 280x170mm 12.9-inch     | 1         | 12.5%   |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 260x140mm 11.6-inch     | 1         | 12.5%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                | 1         | 12.5%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch       | 1         | 12.5%   |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                | 1         | 12.5%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 4         | 50%     |
| 1366x768 (WXGA) | 2         | 25%     |
| 2880x1800       | 1         | 12.5%   |
| 2160x1350       | 1         | 12.5%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 3         | 37.5%   |
| 13     | 2         | 25%     |
| 12     | 2         | 25%     |
| 11     | 1         | 12.5%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 4         | 50%     |
| 201-300     | 4         | 50%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 6         | 75%     |
| 16/10 | 2         | 25%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 2         | 25%     |
| 91-100         | 2         | 25%     |
| 71-80          | 1         | 12.5%   |
| 61-70          | 1         | 12.5%   |
| 51-60          | 1         | 12.5%   |
| 101-110        | 1         | 12.5%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3         | 37.5%   |
| 161-240       | 2         | 25%     |
| More than 240 | 1         | 12.5%   |
| 101-120       | 1         | 12.5%   |
| 51-100        | 1         | 12.5%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 89.47%  |
| 0     | 2         | 10.53%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 15        | 48.39%  |
| Realtek Semiconductor             | 6         | 19.35%  |
| Broadcom                          | 3         | 9.68%   |
| Qualcomm Atheros                  | 2         | 6.45%   |
| TP-Link                           | 1         | 3.23%   |
| Sierra Wireless                   | 1         | 3.23%   |
| Marvell Technology Group          | 1         | 3.23%   |
| Ericsson Business Mobile Networks | 1         | 3.23%   |
| Apple                             | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 4         | 10.26%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 3         | 7.69%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 5.13%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 5.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 5.13%   |
| TP-Link Wireless USB Adapter                                                | 1         | 2.56%   |
| Sierra Wireless EM7305 Modem                                                | 1         | 2.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 1         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 2.56%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                          | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 2.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 2.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 2.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 1         | 2.56%   |
| Intel Wireless 8260                                                         | 1         | 2.56%   |
| Intel Wireless 7260                                                         | 1         | 2.56%   |
| Intel WiFi Link 5100                                                        | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 2.56%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 2.56%   |
| Intel Ethernet Connection I217-LM                                           | 1         | 2.56%   |
| Intel Ethernet Connection (4) I219-V                                        | 1         | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 2.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.56%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 2.56%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                             | 1         | 2.56%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                          | 1         | 2.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.56%   |
| Apple Ethernet Adapter [A1277]                                              | 1         | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 59.09%  |
| Realtek Semiconductor | 4         | 18.18%  |
| Qualcomm Atheros      | 2         | 9.09%   |
| Broadcom              | 2         | 9.09%   |
| TP-Link               | 1         | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 2         | 9.09%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 9.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 9.09%   |
| TP-Link Wireless USB Adapter                                            | 1         | 4.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 4.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 4.55%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                      | 1         | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 4.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 4.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 4.55%   |
| Intel Wireless 8260                                                     | 1         | 4.55%   |
| Intel Wireless 7260                                                     | 1         | 4.55%   |
| Intel WiFi Link 5100                                                    | 1         | 4.55%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 4.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 4.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 4.55%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 4.55%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 8         | 53.33%  |
| Realtek Semiconductor    | 4         | 26.67%  |
| Marvell Technology Group | 1         | 6.67%   |
| Broadcom                 | 1         | 6.67%   |
| Apple                    | 1         | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 26.67%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 6.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 6.67%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 6.67%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 6.67%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 6.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 6.67%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 6.67%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 54.05%  |
| Ethernet | 15        | 40.54%  |
| Unknown  | 2         | 5.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9         | 50%     |
| Ethernet | 9         | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 13        | 68.42%  |
| 1     | 6         | 31.58%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 94.74%  |
| Yes  | 1         | 5.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 61.54%  |
| Broadcom              | 3         | 23.08%  |
| Realtek Semiconductor | 2         | 15.38%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 4         | 30.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 15.38%  |
| Intel AX201 Bluetooth                          | 2         | 15.38%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter        | 1         | 7.69%   |
| Realtek RTL8723B Bluetooth                     | 1         | 7.69%   |
| Broadcom Bluetooth 2.1 Device                  | 1         | 7.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 7.69%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 90.48%  |
| Nvidia | 1         | 4.76%   |
| AMD    | 1         | 4.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 16%     |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 12%     |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 8%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 8%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 8%      |
| Intel 8 Series HD Audio Controller                                         | 2         | 8%      |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 4%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 4%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 4%      |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 4%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 4%      |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 26.09%  |
| Samsung Electronics | 6         | 26.09%  |
| Micron Technology   | 4         | 17.39%  |
| Kingston            | 3         | 13.04%  |
| Unknown             | 2         | 8.7%    |
| Ramaxel Technology  | 1         | 4.35%   |
| 48spaces            | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 7.69%   |
| Unknown                                                                   | 2         | 7.69%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 3.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 3.85%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 3.85%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 3.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 3.85%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 3.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 3.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.85%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 3.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 3.85%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 3.85%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.85%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                              | 1         | 3.85%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s                        | 1         | 3.85%   |
| Micron RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                        | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 3.85%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2400MT/s                   | 1         | 3.85%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                   | 1         | 3.85%   |
| Kingston RAM 9905428-105.A00G 8GB SODIMM DDR3 1333MT/s                    | 1         | 3.85%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 7         | 35%     |
| DDR3   | 7         | 35%     |
| LPDDR3 | 2         | 10%     |
| DDR2   | 2         | 10%     |
| LPDDR5 | 1         | 5%      |
| LPDDR4 | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 84.21%  |
| Row Of Chips | 3         | 15.79%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 39.13%  |
| 8192  | 7         | 30.43%  |
| 2048  | 5         | 21.74%  |
| 16384 | 2         | 8.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 5         | 23.81%  |
| 1600  | 5         | 23.81%  |
| 2400  | 2         | 9.52%   |
| 6400  | 1         | 4.76%   |
| 4267  | 1         | 4.76%   |
| 2133  | 1         | 4.76%   |
| 1867  | 1         | 4.76%   |
| 1334  | 1         | 4.76%   |
| 1333  | 1         | 4.76%   |
| 1067  | 1         | 4.76%   |
| 667   | 1         | 4.76%   |
| 400   | 1         | 4.76%   |

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


| Model                                    | Notebooks | Percent |
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


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Upek                  | 2         | 33.33%  |
| LighTuning Technology | 2         | 33.33%  |
| Validity Sensors      | 1         | 16.67%  |
| Synaptics             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 8         | 42.11%  |
| 1     | 5         | 26.32%  |
| 3     | 3         | 15.79%  |
| 4     | 2         | 10.53%  |
| 0     | 1         | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 16        | 43.24%  |
| Bluetooth                | 7         | 18.92%  |
| Fingerprint reader       | 6         | 16.22%  |
| Net/wireless             | 5         | 13.51%  |
| Card reader              | 2         | 5.41%   |
| Firewire controller      | 1         | 2.7%    |

