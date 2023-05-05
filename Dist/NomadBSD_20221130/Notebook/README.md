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

Total: 14

| Vendor  | Model                       | Probe                                                     | Date         |
|---------|-----------------------------|-----------------------------------------------------------|--------------|
| Samsung | N150/N210/N220              | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo  | ThinkPad X280 20KESB4T00    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Dell    | Latitude 7300               | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Lenovo  | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Acer    | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Intel   | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo  | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Acer    | Aspire 7738                 | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo  | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo  | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| Lenovo  | G50-70 20351                | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo  | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple   | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 12        | 92.31%  |
| i386  | 1         | 7.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| xinitrc | 6         | 46.15%  |
| Openbox | 5         | 38.46%  |
| KDE5    | 2         | 15.38%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 13        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 13        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| fr_FR | 4         | 30.77%  |
| en_GB | 4         | 30.77%  |
| en_US | 3         | 23.08%  |
| lt_LT | 1         | 7.69%   |
| fi_FI | 1         | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 13        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 8         | 61.54%  |
| Zfs  | 5         | 38.46%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 8         | 61.54%  |
| MBR  | 5         | 38.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 53.85%  |
| Acer                | 2         | 15.38%  |
| Samsung Electronics | 1         | 7.69%   |
| Fujitsu             | 1         | 7.69%   |
| Dell                | 1         | 7.69%   |
| Apple               | 1         | 7.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung N150/N210/N220          | 1         | 7.69%   |
| Lenovo Yoga 710-11IKB 80V6      | 1         | 7.69%   |
| Lenovo ThinkPad X280 20KESB4T00 | 1         | 7.69%   |
| Lenovo ThinkPad X230 23255NG    | 1         | 7.69%   |
| Lenovo ThinkPad W520 42844DG    | 1         | 7.69%   |
| Lenovo ThinkPad T470 20HES0EV0A | 1         | 7.69%   |
| Lenovo ThinkPad E14 20RA0036RT  | 1         | 7.69%   |
| Lenovo G50-70 20351             | 1         | 7.69%   |
| Fujitsu CELSIUS H730            | 1         | 7.69%   |
| Dell Latitude 7300              | 1         | 7.69%   |
| Apple MacBookPro14,1            | 1         | 7.69%   |
| Acer Swift SF314-56             | 1         | 7.69%   |
| Acer Aspire 7738                | 1         | 7.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 38.46%  |
| Samsung N150       | 1         | 7.69%   |
| Lenovo Yoga        | 1         | 7.69%   |
| Lenovo G50-70      | 1         | 7.69%   |
| Fujitsu CELSIUS    | 1         | 7.69%   |
| Dell Latitude      | 1         | 7.69%   |
| Apple MacBookPro14 | 1         | 7.69%   |
| Acer Swift         | 1         | 7.69%   |
| Acer Aspire        | 1         | 7.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 2         | 15.38%  |
| 2012 | 2         | 15.38%  |
| 2022 | 1         | 7.69%   |
| 2021 | 1         | 7.69%   |
| 2020 | 1         | 7.69%   |
| 2018 | 1         | 7.69%   |
| 2016 | 1         | 7.69%   |
| 2015 | 1         | 7.69%   |
| 2014 | 1         | 7.69%   |
| 2010 | 1         | 7.69%   |
| 2009 | 1         | 7.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 13        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12        | 92.31%  |
| Yes  | 1         | 7.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 8         | 61.54%  |
| 4.01-8.0   | 1         | 7.69%   |
| 32.01-64.0 | 1         | 7.69%   |
| 24.01-32.0 | 1         | 7.69%   |
| 2.01-3.0   | 1         | 7.69%   |
| 16.01-24.0 | 1         | 7.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 9         | 69.23%  |
| 0.51-1.0 | 3         | 23.08%  |
| 1.01-2.0 | 1         | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 8         | 61.54%  |
| 2      | 3         | 23.08%  |
| 0      | 2         | 15.38%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10        | 76.92%  |
| Yes       | 3         | 23.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 76.92%  |
| No        | 3         | 23.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9         | 69.23%  |
| No        | 4         | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| UK        | 4         | 30.77%  |
| France    | 4         | 30.77%  |
| USA       | 2         | 15.38%  |
| Russia    | 1         | 7.69%   |
| Lithuania | 1         | 7.69%   |
| Finland   | 1         | 7.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Melun          | 2         | 15.38%  |
| West Bromwich  | 1         | 7.69%   |
| Wakefield      | 1         | 7.69%   |
| Vilnius        | 1         | 7.69%   |
| Vaasa          | 1         | 7.69%   |
| Seattle        | 1         | 7.69%   |
| Sartrouville   | 1         | 7.69%   |
| Saint-Raphaël | 1         | 7.69%   |
| Portland       | 1         | 7.69%   |
| Moscow         | 1         | 7.69%   |
| Lincoln        | 1         | 7.69%   |
| Addlestone     | 1         | 7.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 15.38%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| Crucial             | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| UMIS                | 1         | 1      | 7.69%   |
| SPCC                | 1         | 1      | 7.69%   |
| Phison              | 1         | 1      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| Intel               | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 2      | 7.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| WDC WD7500BPKX-00HPJT0 752GB     | 1         | 7.69%   |
| UMIS RPJTJ256MED1OWX 256GB       | 1         | 7.69%   |
| SPCC Solid State Disk 128GB      | 1         | 7.69%   |
| SanDisk X400 M.2 2280 256GB      | 1         | 7.69%   |
| SanDisk pSSD 128GB               | 1         | 7.69%   |
| Samsung SSD 860 EVO M.2 250GB    | 1         | 7.69%   |
| Samsung SSD 850 EVO 2TB          | 1         | 7.69%   |
| Phison Sabrent Rocket nano 512GB | 1         | 7.69%   |
| Kingston SA400S37240G 240GB      | 1         | 7.69%   |
| Intel SSDPEKKF256G8L 256GB       | 1         | 7.69%   |
| Hitachi HTS545050B9A300 500GB    | 1         | 7.69%   |
| Crucial CT256MX100SSD1 256GB     | 1         | 7.69%   |
| Crucial CT2000BX500SSD1 2TB      | 1         | 7.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 2      | 50%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 25%     |
| Samsung Electronics | 2         | 2      | 25%     |
| Crucial             | 2         | 2      | 25%     |
| SPCC                | 1         | 1      | 12.5%   |
| Kingston            | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 8      | 61.54%  |
| NVMe | 3         | 3      | 23.08%  |
| HDD  | 2         | 3      | 15.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9         | 11     | 75%     |
| NVMe | 3         | 3      | 25%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7         | 8      | 70%     |
| 1.01-2.0   | 2         | 2      | 20%     |
| 0.51-1.0   | 1         | 1      | 10%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 7         | 53.85%  |
| 21-50      | 3         | 23.08%  |
| 251-500    | 1         | 7.69%   |
| 101-250    | 1         | 7.69%   |
| 501-1000   | 1         | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 13        | 100%    |

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
| SanDisk pSSD 128GB | 1         | 1      | 100%    |

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
| Works   | 10        | 11     | 83.33%  |
| Malfunc | 1         | 2      | 8.33%   |
| Failed  | 1         | 1      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 12        | 85.71%  |
| Shenzhen Unionmemory Information System | 1         | 7.14%   |
| Phison Electronics                      | 1         | 7.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 14.29%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 14.29%  |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 7.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 7.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 7.14%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 7.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 7.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 7.14%   |
| Unknown                                                                        | 1         | 7.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 9         | 64.29%  |
| NVMe | 3         | 21.43%  |
| RAID | 2         | 14.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 100%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Intel CPU Version                  | 1         | 7.69%   |
| Intel Core i7-8665U CPU @ 1.90GHz  | 1         | 7.69%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz | 1         | 7.69%   |
| Intel Core i7-2630QM CPU @ 2.00GHz | 1         | 7.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz  | 1         | 7.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz  | 1         | 7.69%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz   | 1         | 7.69%   |
| Intel Core i5-7360U CPU @ 2.30GHz  | 1         | 7.69%   |
| Intel Core i5-7300U CPU @ 2.60GHz  | 1         | 7.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz  | 1         | 7.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz | 1         | 7.69%   |
| Intel Core i3-4030U CPU @ 1.90GHz  | 1         | 7.69%   |
| Intel Atom CPU N450 @ 1.66GHz      | 1         | 7.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 7         | 53.85%  |
| Intel Core i7 | 3         | 23.08%  |
| Other         | 1         | 7.69%   |
| Intel Core i3 | 1         | 7.69%   |
| Intel Atom    | 1         | 7.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 6         | 46.15%  |
| 2       | 6         | 46.15%  |
| Unknown | 1         | 7.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 12        | 92.31%  |
| Unknown | 1         | 7.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 11        | 84.62%  |
| 1       | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 53.85%  |
| Haswell     | 2         | 15.38%  |
| SandyBridge | 1         | 7.69%   |
| Penryn      | 1         | 7.69%   |
| IvyBridge   | 1         | 7.69%   |
| Bonnell     | 1         | 7.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 80%     |
| Nvidia | 3         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 13.33%  |
| Nvidia GT216M [GeForce GT 240M]                                           | 1         | 6.67%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 6.67%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 6.67%   |
| Intel UHD Graphics 620                                                    | 1         | 6.67%   |
| Intel Iris Plus Graphics 640                                              | 1         | 6.67%   |
| Intel HD Graphics 620                                                     | 1         | 6.67%   |
| Intel HD Graphics 615                                                     | 1         | 6.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 6.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 6.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 6.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 6.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 9         | 69.23%  |
| Intel + Nvidia | 2         | 15.38%  |
| 2 x Intel      | 1         | 7.69%   |
| 1 x Nvidia     | 1         | 7.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 12        | 92.31%  |
| Proprietary | 1         | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Chimei Innolux      | 1         | 33.33%  |
| Apple               | 1         | 33.33%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 33.33%  |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 260x140mm 11.6-inch     | 1         | 33.33%  |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                | 1         | 33.33%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 2         | 66.67%  |
| 2880x1800       | 1         | 33.33%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 1         | 33.33%  |
| 13     | 1         | 33.33%  |
| 11     | 1         | 33.33%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 201-300     | 2         | 66.67%  |
| 301-350     | 1         | 33.33%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 2         | 66.67%  |
| 16/10 | 1         | 33.33%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 1         | 33.33%  |
| 51-60          | 1         | 33.33%  |
| 91-100         | 1         | 33.33%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| More than 240 | 1         | 33.33%  |
| 161-240       | 1         | 33.33%  |
| 101-120       | 1         | 33.33%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 12        | 92.31%  |
| 0     | 1         | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 10        | 45.45%  |
| Realtek Semiconductor             | 4         | 18.18%  |
| Broadcom                          | 2         | 9.09%   |
| TP-Link                           | 1         | 4.55%   |
| Sierra Wireless                   | 1         | 4.55%   |
| Qualcomm Atheros                  | 1         | 4.55%   |
| Marvell Technology Group          | 1         | 4.55%   |
| Ericsson Business Mobile Networks | 1         | 4.55%   |
| Apple                             | 1         | 4.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 2         | 7.41%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 7.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 2         | 7.41%   |
| TP-Link Wireless USB Adapter                                                | 1         | 3.7%    |
| Sierra Wireless EM7305 Modem                                                | 1         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 3.7%    |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                          | 1         | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 3.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 3.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 1         | 3.7%    |
| Intel Wireless 8260                                                         | 1         | 3.7%    |
| Intel Wireless 7260                                                         | 1         | 3.7%    |
| Intel WiFi Link 5100                                                        | 1         | 3.7%    |
| Intel Ethernet Connection I217-LM                                           | 1         | 3.7%    |
| Intel Ethernet Connection (4) I219-V                                        | 1         | 3.7%    |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 3.7%    |
| Intel Centrino Ultimate-N 6300                                              | 1         | 3.7%    |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 3.7%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                             | 1         | 3.7%    |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                          | 1         | 3.7%    |
| Apple Ethernet Adapter [A1277]                                              | 1         | 3.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 60%     |
| Realtek Semiconductor | 3         | 20%     |
| TP-Link               | 1         | 6.67%   |
| Qualcomm Atheros      | 1         | 6.67%   |
| Broadcom              | 1         | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                          | 2         | 13.33%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]            | 2         | 13.33%  |
| TP-Link Wireless USB Adapter                        | 1         | 6.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter     | 1         | 6.67%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller  | 1         | 6.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter | 1         | 6.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter    | 1         | 6.67%   |
| Intel Wireless 8260                                 | 1         | 6.67%   |
| Intel Wireless 7260                                 | 1         | 6.67%   |
| Intel WiFi Link 5100                                | 1         | 6.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                   | 1         | 6.67%   |
| Intel Centrino Ultimate-N 6300                      | 1         | 6.67%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter  | 1         | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 5         | 50%     |
| Realtek Semiconductor    | 2         | 20%     |
| Marvell Technology Group | 1         | 10%     |
| Broadcom                 | 1         | 10%     |
| Apple                    | 1         | 10%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 20%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 20%     |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 10%     |
| Intel Ethernet Connection I217-LM                                 | 1         | 10%     |
| Intel Ethernet Connection (4) I219-V                              | 1         | 10%     |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 10%     |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 10%     |
| Apple Ethernet Adapter [A1277]                                    | 1         | 10%     |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 13        | 52%     |
| Ethernet | 10        | 40%     |
| Unknown  | 2         | 8%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 6         | 54.55%  |
| WiFi     | 5         | 45.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 9         | 69.23%  |
| 1     | 4         | 30.77%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12        | 92.31%  |
| Yes  | 1         | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 6         | 66.67%  |
| Broadcom              | 2         | 22.22%  |
| Realtek Semiconductor | 1         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 4         | 44.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 22.22%  |
| Realtek RTL8723B Bluetooth                     | 1         | 11.11%  |
| Broadcom Bluetooth 2.1 Device                  | 1         | 11.11%  |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 92.86%  |
| Nvidia | 1         | 7.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 25%     |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 12.5%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 6.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 6.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 6.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 6.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 6.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 6.25%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 6.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 29.41%  |
| SK hynix            | 4         | 23.53%  |
| Kingston            | 3         | 17.65%  |
| Micron Technology   | 2         | 11.76%  |
| Ramaxel Technology  | 1         | 5.88%   |
| 48spaces            | 1         | 5.88%   |
| Unknown             | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 5.26%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 5.26%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 5.26%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 5.26%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 5.26%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 5.26%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 5.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 5.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 5.26%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 5.26%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 5.26%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 5.26%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                              | 1         | 5.26%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 5.26%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR4 2400MT/s                   | 1         | 5.26%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                   | 1         | 5.26%   |
| Kingston RAM 9905428-105.A00G 8GB SODIMM DDR3 1333MT/s                    | 1         | 5.26%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 5.26%   |
| Unknown                                                                   | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 42.86%  |
| DDR3   | 5         | 35.71%  |
| LPDDR3 | 2         | 14.29%  |
| DDR2   | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 12        | 92.31%  |
| Row Of Chips | 1         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 8         | 47.06%  |
| 8192  | 6         | 35.29%  |
| 2048  | 2         | 11.76%  |
| 16384 | 1         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 4         | 26.67%  |
| 1600  | 3         | 20%     |
| 2400  | 2         | 13.33%  |
| 2133  | 1         | 6.67%   |
| 1867  | 1         | 6.67%   |
| 1334  | 1         | 6.67%   |
| 1333  | 1         | 6.67%   |
| 1067  | 1         | 6.67%   |
| 667   | 1         | 6.67%   |

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


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chicony Electronics     | 4         | 40%     |
| Realtek Semiconductor   | 2         | 20%     |
| Z-Star Microelectronics | 1         | 10%     |
| Suyin                   | 1         | 10%     |
| IMC Networks            | 1         | 10%     |
| Bison Electronics       | 1         | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Z-Star Webcam                            | 1         | 10%     |
| Suyin HD Video WebCam                    | 1         | 10%     |
| Realtek Lenovo EasyCamera                | 1         | 10%     |
| Realtek Integrated_Webcam_HD             | 1         | 10%     |
| IMC Networks EasyCamera                  | 1         | 10%     |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 10%     |
| Chicony Integrated Camera                | 1         | 10%     |
| Chicony HD WebCam                        | 1         | 10%     |
| Chicony FJ Camera                        | 1         | 10%     |
| Bison SunplusIT Integrated Camera        | 1         | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 2         | 50%     |
| Validity Sensors      | 1         | 25%     |
| Upek                  | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| LighTuning Fingerprint Reader                          | 1         | 25%     |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 25%     |

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
| 2     | 5         | 38.46%  |
| 1     | 4         | 30.77%  |
| 4     | 2         | 15.38%  |
| 3     | 2         | 15.38%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 11        | 42.31%  |
| Bluetooth                | 5         | 19.23%  |
| Fingerprint reader       | 4         | 15.38%  |
| Net/wireless             | 3         | 11.54%  |
| Card reader              | 2         | 7.69%   |
| Firewire controller      | 1         | 3.85%   |

