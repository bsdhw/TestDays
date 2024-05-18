NomadBSD 20221130 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

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

Total: 8

| Vendor     | Model                   | Probe                                                     | Date         |
|------------|-------------------------|-----------------------------------------------------------|--------------|
| Gigabyte   | H61M-S1                 | [723569d88a](https://bsd-hardware.info/?probe=723569d88a) | Oct 01, 2023 |
| Gigabyte   | H61M-S1                 | [8816b1ac4a](https://bsd-hardware.info/?probe=8816b1ac4a) | Sep 29, 2023 |
| Lenovo     | SHARKBAY SDK0E50510 WIN | [66f982c40b](https://bsd-hardware.info/?probe=66f982c40b) | Aug 23, 2023 |
| ASRockRack | C226M WS                | [06a8ca514a](https://bsd-hardware.info/?probe=06a8ca514a) | Apr 14, 2023 |
| ECS        | Z77H2-AX                | [32a290eb5f](https://bsd-hardware.info/?probe=32a290eb5f) | Apr 13, 2023 |
| ASRock     | N68-S UCC               | [04f43c3d70](https://bsd-hardware.info/?probe=04f43c3d70) | Feb 23, 2023 |
| HP         | 1589                    | [8a927b43cb](https://bsd-hardware.info/?probe=8a927b43cb) | Jan 26, 2023 |
| ASUSTek    | ROG STRIX B550-F GAMING | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 7        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Openbox       | 5        | 71.43%  |
| Enlightenment | 2        | 28.57%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 7        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 5        | 71.43%  |
| LightDM | 2        | 28.57%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 3        | 42.86%  |
| Unknown | 2        | 28.57%  |
| zh_TW   | 1        | 14.29%  |
| bg_BG   | 1        | 14.29%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 7        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 4        | 57.14%  |
| Ufs  | 3        | 42.86%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 4        | 57.14%  |
| GPT  | 3        | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Lenovo              | 1        | 14.29%  |
| Hewlett-Packard     | 1        | 14.29%  |
| Gigabyte Technology | 1        | 14.29%  |
| ECS                 | 1        | 14.29%  |
| ASUSTek Computer    | 1        | 14.29%  |
| ASRockRack          | 1        | 14.29%  |
| ASRock              | 1        | 14.29%  |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Lenovo ThinkCentre M93p 10AAS4EN00 | 1        | 14.29%  |
| HP Z420 Workstation                | 1        | 14.29%  |
| Gigabyte H61M-S1                   | 1        | 14.29%  |
| ECS Z77H2-AX                       | 1        | 14.29%  |
| ASUS ROG STRIX B550-F GAMING       | 1        | 14.29%  |
| ASRockRack C226M WS                | 1        | 14.29%  |
| ASRock N68-S UCC                   | 1        | 14.29%  |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Lenovo ThinkCentre | 1        | 14.29%  |
| HP Z420            | 1        | 14.29%  |
| Gigabyte H61M-S1   | 1        | 14.29%  |
| ECS Z77H2-AX       | 1        | 14.29%  |
| ASUS ROG           | 1        | 14.29%  |
| ASRockRack C226M   | 1        | 14.29%  |
| ASRock N68-S       | 1        | 14.29%  |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 2        | 28.57%  |
| 2020 | 1        | 14.29%  |
| 2018 | 1        | 14.29%  |
| 2015 | 1        | 14.29%  |
| 2012 | 1        | 14.29%  |
| 2011 | 1        | 14.29%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 7        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 7        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 3        | 42.86%  |
| 32.01-64.0 | 2        | 28.57%  |
| 16.01-24.0 | 2        | 28.57%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 3        | 42.86%  |
| 1.01-2.0 | 2        | 28.57%  |
| 0.01-0.5 | 2        | 28.57%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 4        | 57.14%  |
| 4      | 1        | 14.29%  |
| 3      | 1        | 14.29%  |
| 2      | 1        | 14.29%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 85.71%  |
| Yes       | 1        | 14.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 85.71%  |
| No        | 1        | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 85.71%  |
| Yes       | 1        | 14.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 71.43%  |
| Yes       | 2        | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 2        | 28.57%  |
| Taiwan      | 1        | 14.29%  |
| Netherlands | 1        | 14.29%  |
| France      | 1        | 14.29%  |
| Bulgaria    | 1        | 14.29%  |
| Argentina   | 1        | 14.29%  |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Lutherville-Timonium | 2        | 28.57%  |
| Urcuit               | 1        | 14.29%  |
| Taipei               | 1        | 14.29%  |
| Sofia                | 1        | 14.29%  |
| Eindhoven            | 1        | 14.29%  |
| Córdoba             | 1        | 14.29%  |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 30%     |
| Samsung Electronics | 3        | 4      | 30%     |
| WDC                 | 2        | 2      | 20%     |
| Kingston            | 1        | 2      | 10%     |
| Corsair             | 1        | 1      | 10%     |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD40EFAX-68JH4N0 4TB         | 1        | 8.33%   |
| WDC WD30EZRZ-00GXCB0 3TB         | 1        | 8.33%   |
| Seagate ST9250315AS 250GB        | 1        | 8.33%   |
| Seagate ST310212A 10GB           | 1        | 8.33%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 8.33%   |
| Samsung SSD 970 EVO Plus 2TB     | 1        | 8.33%   |
| Samsung SSD 970 EVO Plus 1TB     | 1        | 8.33%   |
| Samsung SSD 850 EVO mSATA 1TB    | 1        | 8.33%   |
| Samsung MZ7LN256HCHP-000L1 256GB | 1        | 8.33%   |
| Kingston SA400S37240G 240GB      | 1        | 8.33%   |
| Kingston SA400M8240G 240GB       | 1        | 8.33%   |
| Corsair MP600 GS 1TB             | 1        | 8.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 60%     |
| WDC     | 2        | 2      | 40%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 66.67%  |
| Kingston            | 1        | 2      | 33.33%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 3        | 4      | 42.86%  |
| HDD  | 3        | 5      | 42.86%  |
| NVMe | 1        | 3      | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 5        | 9      | 83.33%  |
| NVMe | 1        | 3      | 16.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 3        | 5      | 42.86%  |
| 0.51-1.0   | 2        | 2      | 28.57%  |
| 3.01-4.0   | 1        | 1      | 14.29%  |
| 2.01-3.0   | 1        | 1      | 14.29%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 4        | 57.14%  |
| 101-250    | 2        | 28.57%  |
| 51-100     | 1        | 14.29%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 7        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST9250315AS 250GB | 1        | 1      | 50%     |
| Seagate ST310212A 10GB    | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 5        | 10     | 71.43%  |
| Malfunc | 2        | 2      | 28.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 5        | 50%     |
| Samsung Electronics | 1        | 10%     |
| Phison Electronics  | 1        | 10%     |
| Nvidia              | 1        | 10%     |
| ASMedia Technology  | 1        | 10%     |
| AMD                 | 1        | 10%     |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 13.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 6.67%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                                     | 1        | 6.67%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 6.67%   |
| Nvidia MCP61 IDE                                                                        | 1        | 6.67%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 6.67%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                                | 1        | 6.67%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                                | 1        | 6.67%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 6.67%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 6.67%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 1        | 6.67%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 6.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 4        | 40%     |
| SATA | 4        | 40%     |
| SAS  | 1        | 10%     |
| NVMe | 1        | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 5        | 71.43%  |
| AMD    | 2        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 1        | 14.29%  |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz    | 1        | 14.29%  |
| Intel Core i7-3770K CPU @ 3.50GHz      | 1        | 14.29%  |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 14.29%  |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 14.29%  |
| AMD Ryzen 7 5700G with Radeon Graphics | 1        | 14.29%  |
| AMD Phenom II X4 945 Processor         | 1        | 14.29%  |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Xeon       | 2        | 28.57%  |
| Intel Core i5    | 2        | 28.57%  |
| Intel Core i7    | 1        | 14.29%  |
| AMD Ryzen 7      | 1        | 14.29%  |
| AMD Phenom II X4 | 1        | 14.29%  |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 5        | 71.43%  |
| 16     | 1        | 14.29%  |
| 6      | 1        | 14.29%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4        | 57.14%  |
| 2      | 3        | 42.86%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| IvyBridge | 3        | 42.86%  |
| Haswell   | 2        | 28.57%  |
| Zen 3     | 1        | 14.29%  |
| K10       | 1        | 14.29%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 3        | 42.86%  |
| Intel  | 2        | 28.57%  |
| AMD    | 2        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP102 [TITAN X]                                                      | 1        | 14.29%  |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 14.29%  |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 14.29%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 14.29%  |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 14.29%  |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 1        | 14.29%  |
| AMD Cape Verde GL [FirePro W4100]                                           | 1        | 14.29%  |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 3        | 42.86%  |
| 1 x Intel  | 2        | 28.57%  |
| 1 x AMD    | 2        | 28.57%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 5        | 71.43%  |
| Proprietary | 2        | 28.57%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 85.71%  |
| 3.01-4.0   | 1        | 14.29%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| ViewSonic     | 2        | 66.67%  |
| NEC Computers | 1        | 33.33%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch    | 1        | 33.33%  |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch | 1        | 33.33%  |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch  | 1        | 33.33%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 2        | 66.67%  |
| 2560x1440 (QHD) | 1        | 33.33%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 1        | 33.33%  |
| 24     | 1        | 33.33%  |
| 23     | 1        | 33.33%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 3        | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 3        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2        | 66.67%  |
| 301-350        | 1        | 33.33%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2        | 66.67%  |
| 101-120 | 1        | 33.33%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4        | 57.14%  |
| 0     | 3        | 42.86%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 50%     |
| Realtek Semiconductor | 2        | 25%     |
| Samsung Electronics   | 1        | 12.5%   |
| Qualcomm Atheros      | 1        | 12.5%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2        | 22.22%  |
| Intel Ethernet Connection I217-LM                                      | 2        | 22.22%  |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 11.11%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 11.11%  |
| Intel I210 Gigabit Network Connection                                  | 1        | 11.11%  |
| Intel Ethernet Controller I225-V                                       | 1        | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 11.11%  |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Qualcomm Atheros | 1        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter | 1        | 100%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 57.14%  |
| Realtek Semiconductor | 2        | 28.57%  |
| Samsung Electronics   | 1        | 14.29%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2        | 25%     |
| Intel Ethernet Connection I217-LM                                      | 2        | 25%     |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 12.5%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 12.5%   |
| Intel Ethernet Controller I225-V                                       | 1        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 12.5%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 6        | 85.71%  |
| WiFi     | 1        | 14.29%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5        | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5        | 71.43%  |
| 3     | 1        | 14.29%  |
| 0     | 1        | 14.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 6        | 85.71%  |
| Yes  | 1        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 1        | 50%     |
| Cambridge Silicon Radio         | 1        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Qualcomm Atheros AR3011 Bluetooth (no firmware)     | 1        | 50%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 41.67%  |
| Nvidia                  | 3        | 25%     |
| AMD                     | 2        | 16.67%  |
| Creative Labs           | 1        | 8.33%   |
| BEHRINGER International | 1        | 8.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 12.5%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 12.5%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 6.25%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 6.25%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 6.25%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 6.25%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 6.25%   |
| BEHRINGER International UMC 202HD 192k                                     | 1        | 6.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 6.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 6.25%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 6.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 28.57%  |
| Kingston            | 2        | 28.57%  |
| Transcend           | 1        | 14.29%  |
| Corsair             | 1        | 14.29%  |
| Unknown             | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s     | 1        | 12.5%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s     | 1        | 12.5%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 12.5%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s   | 1        | 12.5%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s   | 1        | 12.5%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s | 1        | 12.5%   |
| Corsair RAM CMY16GX3M2A2133C11 8GB DIMM DDR3 1866MT/s | 1        | 12.5%   |
| Unknown                                               | 1        | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 5        | 71.43%  |
| DDR4 | 1        | 14.29%  |
| DDR2 | 1        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 6        | 85.71%  |
| SODIMM | 1        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 6        | 75%     |
| 4096 | 2        | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 42.86%  |
| 3600  | 1        | 14.29%  |
| 1866  | 1        | 14.29%  |
| 1333  | 1        | 14.29%  |
| 533   | 1        | 14.29%  |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3        | 42.86%  |
| 0     | 2        | 28.57%  |
| 7     | 1        | 14.29%  |
| 2     | 1        | 14.29%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 4        | 44.44%  |
| Firewire controller      | 2        | 22.22%  |
| Sound                    | 1        | 11.11%  |
| Net/wireless             | 1        | 11.11%  |
| Bluetooth                | 1        | 11.11%  |

