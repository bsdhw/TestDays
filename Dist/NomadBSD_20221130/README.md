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

Total: 19

| Vendor     | Model                       | Form-Factor | Probe                                                     | Date         |
|------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASRockRack | C226M WS                    | Desktop     | [06a8ca514a](https://bsd-hardware.info/?probe=06a8ca514a) | Apr 14, 2023 |
| ECS        | Z77H2-AX                    | Desktop     | [32a290eb5f](https://bsd-hardware.info/?probe=32a290eb5f) | Apr 13, 2023 |
| Samsung    | N150/N210/N220              | Notebook    | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo     | ThinkPad X280 20KESB4T00    | Notebook    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Dell       | Latitude 7300               | Notebook    | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Lenovo     | ThinkPad X230 23255NG       | Notebook    | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Acer       | Swift SF314-56              | Notebook    | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Intel      | Jasper Lake Client Platf... | Notebook    | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo     | ThinkPad T470 20HES0EV0A    | Notebook    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu    | CELSIUS H730                | Notebook    | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| ASRock     | N68-S UCC                   | Desktop     | [04f43c3d70](https://bsd-hardware.info/?probe=04f43c3d70) | Feb 23, 2023 |
| Acer       | Aspire 7738                 | Notebook    | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo     | ThinkPad W520 42844DG       | Notebook    | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo     | ThinkPad E14 20RA0036RT     | Notebook    | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| HP         | 1589                        | Desktop     | [8a927b43cb](https://bsd-hardware.info/?probe=8a927b43cb) | Jan 26, 2023 |
| ASUSTek    | ROG STRIX B550-F GAMING     | Desktop     | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |
| Lenovo     | G50-70 20351                | Notebook    | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo     | Yoga 710-11IKB 80V6         | Notebook    | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple      | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 17        | 94.44%  |
| i386  | 1         | 5.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 8         | 44.44%  |
| xinitrc       | 6         | 33.33%  |
| KDE5          | 2         | 11.11%  |
| Enlightenment | 2         | 11.11%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 18        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 16        | 88.89%  |
| LightDM | 2         | 11.11%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 6         | 33.33%  |
| fr_FR   | 4         | 22.22%  |
| en_GB   | 4         | 22.22%  |
| lt_LT   | 1         | 5.56%   |
| fi_FI   | 1         | 5.56%   |
| bg_BG   | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 18        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 10        | 55.56%  |
| Zfs  | 8         | 44.44%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 11        | 61.11%  |
| MBR  | 7         | 38.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 38.89%  |
| Acer                | 2         | 11.11%  |
| Samsung Electronics | 1         | 5.56%   |
| Hewlett-Packard     | 1         | 5.56%   |
| Fujitsu             | 1         | 5.56%   |
| ECS                 | 1         | 5.56%   |
| Dell                | 1         | 5.56%   |
| ASUSTek Computer    | 1         | 5.56%   |
| ASRockRack          | 1         | 5.56%   |
| ASRock              | 1         | 5.56%   |
| Apple               | 1         | 5.56%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung N150/N210/N220          | 1         | 5.56%   |
| Lenovo Yoga 710-11IKB 80V6      | 1         | 5.56%   |
| Lenovo ThinkPad X280 20KESB4T00 | 1         | 5.56%   |
| Lenovo ThinkPad X230 23255NG    | 1         | 5.56%   |
| Lenovo ThinkPad W520 42844DG    | 1         | 5.56%   |
| Lenovo ThinkPad T470 20HES0EV0A | 1         | 5.56%   |
| Lenovo ThinkPad E14 20RA0036RT  | 1         | 5.56%   |
| Lenovo G50-70 20351             | 1         | 5.56%   |
| HP Z420 Workstation             | 1         | 5.56%   |
| Fujitsu CELSIUS H730            | 1         | 5.56%   |
| ECS Z77H2-AX                    | 1         | 5.56%   |
| Dell Latitude 7300              | 1         | 5.56%   |
| ASUS ROG STRIX B550-F GAMING    | 1         | 5.56%   |
| ASRockRack C226M WS             | 1         | 5.56%   |
| ASRock N68-S UCC                | 1         | 5.56%   |
| Apple MacBookPro14,1            | 1         | 5.56%   |
| Acer Swift SF314-56             | 1         | 5.56%   |
| Acer Aspire 7738                | 1         | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 27.78%  |
| Samsung N150       | 1         | 5.56%   |
| Lenovo Yoga        | 1         | 5.56%   |
| Lenovo G50-70      | 1         | 5.56%   |
| HP Z420            | 1         | 5.56%   |
| Fujitsu CELSIUS    | 1         | 5.56%   |
| ECS Z77H2-AX       | 1         | 5.56%   |
| Dell Latitude      | 1         | 5.56%   |
| ASUS ROG           | 1         | 5.56%   |
| ASRockRack C226M   | 1         | 5.56%   |
| ASRock N68-S       | 1         | 5.56%   |
| Apple MacBookPro14 | 1         | 5.56%   |
| Acer Swift         | 1         | 5.56%   |
| Acer Aspire        | 1         | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 3         | 16.67%  |
| 2020 | 2         | 11.11%  |
| 2019 | 2         | 11.11%  |
| 2018 | 2         | 11.11%  |
| 2022 | 1         | 5.56%   |
| 2021 | 1         | 5.56%   |
| 2016 | 1         | 5.56%   |
| 2015 | 1         | 5.56%   |
| 2014 | 1         | 5.56%   |
| 2013 | 1         | 5.56%   |
| 2011 | 1         | 5.56%   |
| 2010 | 1         | 5.56%   |
| 2009 | 1         | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 13        | 72.22%  |
| Desktop  | 5         | 27.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 17        | 94.44%  |
| Yes  | 1         | 5.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 9         | 50%     |
| 32.01-64.0 | 3         | 16.67%  |
| 16.01-24.0 | 3         | 16.67%  |
| 4.01-8.0   | 1         | 5.56%   |
| 24.01-32.0 | 1         | 5.56%   |
| 2.01-3.0   | 1         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 9         | 50%     |
| 0.51-1.0 | 6         | 33.33%  |
| 1.01-2.0 | 3         | 16.67%  |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 10        | 55.56%  |
| 2      | 4         | 22.22%  |
| 0      | 2         | 11.11%  |
| 4      | 1         | 5.56%   |
| 3      | 1         | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 15        | 83.33%  |
| Yes       | 3         | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 77.78%  |
| No        | 4         | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 77.78%  |
| No        | 4         | 22.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11        | 61.11%  |
| No        | 7         | 38.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 4         | 22.22%  |
| UK          | 4         | 22.22%  |
| France      | 4         | 22.22%  |
| Russia      | 1         | 5.56%   |
| Netherlands | 1         | 5.56%   |
| Lithuania   | 1         | 5.56%   |
| Finland     | 1         | 5.56%   |
| Bulgaria    | 1         | 5.56%   |
| Argentina   | 1         | 5.56%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Melun                | 2         | 11.11%  |
| Lutherville-Timonium | 2         | 11.11%  |
| West Bromwich        | 1         | 5.56%   |
| Wakefield            | 1         | 5.56%   |
| Vilnius              | 1         | 5.56%   |
| Vaasa                | 1         | 5.56%   |
| Sofia                | 1         | 5.56%   |
| Seattle              | 1         | 5.56%   |
| Sartrouville         | 1         | 5.56%   |
| Saint-Raphaël       | 1         | 5.56%   |
| Portland             | 1         | 5.56%   |
| Moscow               | 1         | 5.56%   |
| Lincoln              | 1         | 5.56%   |
| Eindhoven            | 1         | 5.56%   |
| Córdoba             | 1         | 5.56%   |
| Addlestone           | 1         | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 18.18%  |
| WDC                 | 3         | 3      | 13.64%  |
| Seagate             | 3         | 3      | 13.64%  |
| SanDisk             | 2         | 2      | 9.09%   |
| Kingston            | 2         | 3      | 9.09%   |
| Crucial             | 2         | 2      | 9.09%   |
| UMIS                | 1         | 1      | 4.55%   |
| SPCC                | 1         | 1      | 4.55%   |
| Phison              | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| Hitachi             | 1         | 2      | 4.55%   |
| Corsair             | 1         | 1      | 4.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB      | 2         | 8.33%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1         | 4.17%   |
| WDC WD40EFAX-68JH4N0 4TB         | 1         | 4.17%   |
| WDC WD30EZRZ-00GXCB0 3TB         | 1         | 4.17%   |
| UMIS RPJTJ256MED1OWX 256GB       | 1         | 4.17%   |
| SPCC Solid State Disk 128GB      | 1         | 4.17%   |
| Seagate ST9250315AS 250GB        | 1         | 4.17%   |
| Seagate ST310212A 10GB           | 1         | 4.17%   |
| Seagate ST1000DM010-2EP102 1TB   | 1         | 4.17%   |
| SanDisk X400 M.2 2280 256GB      | 1         | 4.17%   |
| SanDisk pSSD 128GB               | 1         | 4.17%   |
| Samsung SSD 970 EVO Plus 2TB     | 1         | 4.17%   |
| Samsung SSD 970 EVO Plus 1TB     | 1         | 4.17%   |
| Samsung SSD 860 EVO M.2 250GB    | 1         | 4.17%   |
| Samsung SSD 850 EVO mSATA 1TB    | 1         | 4.17%   |
| Samsung SSD 850 EVO 2TB          | 1         | 4.17%   |
| Phison Sabrent Rocket nano 512GB | 1         | 4.17%   |
| Kingston SA400M8240G 240GB       | 1         | 4.17%   |
| Intel SSDPEKKF256G8L 256GB       | 1         | 4.17%   |
| Hitachi HTS545050B9A300 500GB    | 1         | 4.17%   |
| Crucial CT256MX100SSD1 256GB     | 1         | 4.17%   |
| Crucial CT2000BX500SSD1 2TB      | 1         | 4.17%   |
| Corsair MP600 GS 1TB             | 1         | 4.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 42.86%  |
| Seagate | 3         | 3      | 42.86%  |
| Hitachi | 1         | 2      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 30%     |
| SanDisk             | 2         | 2      | 20%     |
| Kingston            | 2         | 3      | 20%     |
| Crucial             | 2         | 2      | 20%     |
| SPCC                | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 10        | 11     | 52.63%  |
| HDD  | 5         | 8      | 26.32%  |
| NVMe | 4         | 6      | 21.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 19     | 76.47%  |
| NVMe | 4         | 6      | 23.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 12     | 56.25%  |
| 0.51-1.0   | 3         | 3      | 18.75%  |
| 1.01-2.0   | 2         | 2      | 12.5%   |
| 3.01-4.0   | 1         | 1      | 6.25%   |
| 2.01-3.0   | 1         | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 9         | 50%     |
| 21-50      | 3         | 16.67%  |
| 101-250    | 3         | 16.67%  |
| 251-500    | 1         | 5.56%   |
| 501-1000   | 1         | 5.56%   |
| 51-100     | 1         | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 18        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB     | 1         | 1      | 33.33%  |
| Seagate ST310212A 10GB        | 1         | 1      | 33.33%  |
| Hitachi HTS545050B9A300 500GB | 1         | 2      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model              | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 128GB | 1         | 1      | 100%    |

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
| Works   | 14        | 20     | 77.78%  |
| Malfunc | 3         | 4      | 16.67%  |
| Failed  | 1         | 1      | 5.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 15        | 68.18%  |
| Phison Electronics                      | 2         | 9.09%   |
| Shenzhen Unionmemory Information System | 1         | 4.55%   |
| Samsung Electronics                     | 1         | 4.55%   |
| Nvidia                                  | 1         | 4.55%   |
| ASMedia Technology                      | 1         | 4.55%   |
| AMD                                     | 1         | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 7.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 7.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 7.69%   |
| Unknown                                                                        | 2         | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 3.85%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 3.85%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 3.85%   |
| Nvidia MCP61 IDE                                                               | 1         | 3.85%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 3.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 3.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 3.85%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1         | 3.85%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1         | 3.85%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                       | 1         | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 3.85%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 3.85%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 3.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 3.85%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 3.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 12        | 54.55%  |
| NVMe | 4         | 18.18%  |
| IDE  | 3         | 13.64%  |
| RAID | 2         | 9.09%   |
| SAS  | 1         | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 16        | 88.89%  |
| AMD    | 2         | 11.11%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 1         | 5.56%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz    | 1         | 5.56%   |
| Intel CPU Version                      | 1         | 5.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 5.56%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz     | 1         | 5.56%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 1         | 5.56%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 1         | 5.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 5.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 5.56%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz       | 1         | 5.56%   |
| Intel Core i5-7360U CPU @ 2.30GHz      | 1         | 5.56%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 1         | 5.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 5.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz     | 1         | 5.56%   |
| Intel Core i3-4030U CPU @ 1.90GHz      | 1         | 5.56%   |
| Intel Atom CPU N450 @ 1.66GHz          | 1         | 5.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 1         | 5.56%   |
| AMD Phenom II X4 945 Processor         | 1         | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 7         | 38.89%  |
| Intel Core i7    | 4         | 22.22%  |
| Intel Xeon       | 2         | 11.11%  |
| Other            | 1         | 5.56%   |
| Intel Core i3    | 1         | 5.56%   |
| Intel Atom       | 1         | 5.56%   |
| AMD Ryzen 7      | 1         | 5.56%   |
| AMD Phenom II X4 | 1         | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 9         | 50%     |
| 2       | 6         | 33.33%  |
| 16      | 1         | 5.56%   |
| 6       | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 17        | 94.44%  |
| Unknown | 1         | 5.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 14        | 77.78%  |
| 1       | 3         | 16.67%  |
| Unknown | 1         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 38.89%  |
| IvyBridge   | 3         | 16.67%  |
| Haswell     | 3         | 16.67%  |
| Zen 3       | 1         | 5.56%   |
| SandyBridge | 1         | 5.56%   |
| Penryn      | 1         | 5.56%   |
| K10         | 1         | 5.56%   |
| Bonnell     | 1         | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 13        | 65%     |
| Nvidia | 5         | 25%     |
| AMD    | 2         | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 10%     |
| Nvidia GT216M [GeForce GT 240M]                                           | 1         | 5%      |
| Nvidia GP102 [TITAN X]                                                    | 1         | 5%      |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 5%      |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 5%      |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                   | 1         | 5%      |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller            | 1         | 5%      |
| Intel UHD Graphics 620                                                    | 1         | 5%      |
| Intel Iris Plus Graphics 640                                              | 1         | 5%      |
| Intel HD Graphics 620                                                     | 1         | 5%      |
| Intel HD Graphics 615                                                     | 1         | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 5%      |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 5%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 5%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 5%      |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                           | 1         | 5%      |
| AMD Cape Verde GL [FirePro W4100]                                         | 1         | 5%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 10        | 55.56%  |
| 1 x Nvidia     | 3         | 16.67%  |
| Intel + Nvidia | 2         | 11.11%  |
| 1 x AMD        | 2         | 11.11%  |
| 2 x Intel      | 1         | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 16        | 88.89%  |
| Proprietary | 2         | 11.11%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 25%     |
| NEC Computers       | 1         | 25%     |
| Chimei Innolux      | 1         | 25%     |
| Apple               | 1         | 25%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 25%     |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch         | 1         | 25%     |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 260x140mm 11.6-inch     | 1         | 25%     |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                | 1         | 25%     |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 2         | 50%     |
| 2880x1800       | 1         | 25%     |
| 2560x1440 (QHD) | 1         | 25%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 27     | 1         | 25%     |
| 15     | 1         | 25%     |
| 13     | 1         | 25%     |
| 11     | 1         | 25%     |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 2         | 50%     |
| 501-600     | 1         | 25%     |
| 301-350     | 1         | 25%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 3         | 75%     |
| 16/10 | 1         | 25%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 1         | 25%     |
| 51-60          | 1         | 25%     |
| 301-350        | 1         | 25%     |
| 91-100         | 1         | 25%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 2         | 50%     |
| More than 240 | 1         | 25%     |
| 161-240       | 1         | 25%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 14        | 77.78%  |
| 0     | 4         | 22.22%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 13        | 48.15%  |
| Realtek Semiconductor             | 5         | 18.52%  |
| Qualcomm Atheros                  | 2         | 7.41%   |
| Broadcom                          | 2         | 7.41%   |
| TP-Link                           | 1         | 3.7%    |
| Sierra Wireless                   | 1         | 3.7%    |
| Marvell Technology Group          | 1         | 3.7%    |
| Ericsson Business Mobile Networks | 1         | 3.7%    |
| Apple                             | 1         | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 3         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 3         | 9.09%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 6.06%   |
| Intel Ethernet Connection I217-LM                                           | 2         | 6.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 6.06%   |
| TP-Link Wireless USB Adapter                                                | 1         | 3.03%   |
| Sierra Wireless EM7305 Modem                                                | 1         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 3.03%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                          | 1         | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 3.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 3.03%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 1         | 3.03%   |
| Intel Wireless 8260                                                         | 1         | 3.03%   |
| Intel Wireless 7260                                                         | 1         | 3.03%   |
| Intel WiFi Link 5100                                                        | 1         | 3.03%   |
| Intel I210 Gigabit Network Connection                                       | 1         | 3.03%   |
| Intel Ethernet Controller I225-V                                            | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-V                                        | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 3.03%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 3.03%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 3.03%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                             | 1         | 3.03%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                          | 1         | 3.03%   |
| Apple Ethernet Adapter [A1277]                                              | 1         | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 56.25%  |
| Realtek Semiconductor | 3         | 18.75%  |
| Qualcomm Atheros      | 2         | 12.5%   |
| TP-Link               | 1         | 6.25%   |
| Broadcom              | 1         | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                          | 2         | 12.5%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]            | 2         | 12.5%   |
| TP-Link Wireless USB Adapter                        | 1         | 6.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter     | 1         | 6.25%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller  | 1         | 6.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter | 1         | 6.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter    | 1         | 6.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter    | 1         | 6.25%   |
| Intel Wireless 8260                                 | 1         | 6.25%   |
| Intel Wireless 7260                                 | 1         | 6.25%   |
| Intel WiFi Link 5100                                | 1         | 6.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                   | 1         | 6.25%   |
| Intel Centrino Ultimate-N 6300                      | 1         | 6.25%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter  | 1         | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 8         | 57.14%  |
| Realtek Semiconductor    | 3         | 21.43%  |
| Marvell Technology Group | 1         | 7.14%   |
| Broadcom                 | 1         | 7.14%   |
| Apple                    | 1         | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 20%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 20%     |
| Intel Ethernet Connection I217-LM                                 | 2         | 13.33%  |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 6.67%   |
| Intel I210 Gigabit Network Connection                             | 1         | 6.67%   |
| Intel Ethernet Controller I225-V                                  | 1         | 6.67%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 6.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 6.67%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 6.67%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 14        | 46.67%  |
| Ethernet | 14        | 46.67%  |
| Unknown  | 2         | 6.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10        | 66.67%  |
| WiFi     | 5         | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 9         | 50%     |
| 1     | 7         | 38.89%  |
| 3     | 1         | 5.56%   |
| 0     | 1         | 5.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 16        | 88.89%  |
| Yes  | 2         | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 54.55%  |
| Broadcom                        | 2         | 18.18%  |
| Realtek Semiconductor           | 1         | 9.09%   |
| Qualcomm Atheros Communications | 1         | 9.09%   |
| Cambridge Silicon Radio         | 1         | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 36.36%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 18.18%  |
| Realtek RTL8723B Bluetooth                          | 1         | 9.09%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)     | 1         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 9.09%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 9.09%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 16        | 69.57%  |
| Nvidia                  | 3         | 13.04%  |
| AMD                     | 2         | 8.7%    |
| Creative Labs           | 1         | 4.35%   |
| BEHRINGER International | 1         | 4.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 14.29%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 7.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 7.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 7.14%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 3.57%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 3.57%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 3.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.57%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 3.57%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 3.57%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 3.57%   |
| BEHRINGER International UMC 202HD 192k                                     | 1         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 3.57%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 3.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 3.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 3.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 27.27%  |
| Kingston            | 5         | 22.73%  |
| SK hynix            | 4         | 18.18%  |
| Micron Technology   | 2         | 9.09%   |
| Unknown             | 2         | 9.09%   |
| Ramaxel Technology  | 1         | 4.55%   |
| Corsair             | 1         | 4.55%   |
| 48spaces            | 1         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 2         | 8.33%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 4.17%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 4.17%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 4.17%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 4.17%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 4.17%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 4.17%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 4.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 4.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 4.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 4.17%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s                       | 1         | 4.17%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 4.17%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 4.17%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                              | 1         | 4.17%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 4.17%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s                       | 1         | 4.17%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR4 2400MT/s                   | 1         | 4.17%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                   | 1         | 4.17%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s                     | 1         | 4.17%   |
| Kingston RAM 9905428-105.A00G 8GB SODIMM DDR3 1333MT/s                    | 1         | 4.17%   |
| Corsair RAM CMY16GX3M2A2133C11 8GB DIMM DDR3 1866MT/s                     | 1         | 4.17%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 8         | 42.11%  |
| DDR4   | 7         | 36.84%  |
| LPDDR3 | 2         | 10.53%  |
| DDR2   | 2         | 10.53%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 12        | 66.67%  |
| DIMM         | 5         | 27.78%  |
| Row Of Chips | 1         | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 45.45%  |
| 4096  | 9         | 40.91%  |
| 2048  | 2         | 9.09%   |
| 16384 | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 5         | 25%     |
| 2667  | 4         | 20%     |
| 2400  | 2         | 10%     |
| 3600  | 1         | 5%      |
| 2133  | 1         | 5%      |
| 1867  | 1         | 5%      |
| 1866  | 1         | 5%      |
| 1334  | 1         | 5%      |
| 1333  | 1         | 5%      |
| 1067  | 1         | 5%      |
| 667   | 1         | 5%      |
| 533   | 1         | 5%      |

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


| Vendor                  | Computers | Percent |
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

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
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

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 2         | 50%     |
| Validity Sensors      | 1         | 25%     |
| Upek                  | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6         | 33.33%  |
| 1     | 5         | 27.78%  |
| 4     | 2         | 11.11%  |
| 3     | 2         | 11.11%  |
| 0     | 2         | 11.11%  |
| 7     | 1         | 5.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 13        | 39.39%  |
| Bluetooth                | 6         | 18.18%  |
| Net/wireless             | 4         | 12.12%  |
| Fingerprint reader       | 4         | 12.12%  |
| Firewire controller      | 3         | 9.09%   |
| Card reader              | 2         | 6.06%   |
| Sound                    | 1         | 3.03%   |

