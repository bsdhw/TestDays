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

Total: 24

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 21        | 95.45%  |
| i386  | 1         | 4.55%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Openbox       | 12        | 54.55%  |
| xinitrc       | 6         | 27.27%  |
| KDE5          | 2         | 9.09%   |
| Enlightenment | 2         | 9.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 22        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 20        | 90.91%  |
| LightDM | 2         | 9.09%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 8         | 36.36%  |
| fr_FR   | 4         | 18.18%  |
| en_GB   | 4         | 18.18%  |
| fi_FI   | 2         | 9.09%   |
| Unknown | 2         | 9.09%   |
| lt_LT   | 1         | 4.55%   |
| bg_BG   | 1         | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 22        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 13        | 59.09%  |
| Zfs  | 9         | 40.91%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 14        | 63.64%  |
| MBR  | 8         | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 8         | 36.36%  |
| Hewlett-Packard     | 2         | 9.09%   |
| Acer                | 2         | 9.09%   |
| Samsung Electronics | 1         | 4.55%   |
| Fujitsu Siemens     | 1         | 4.55%   |
| Fujitsu             | 1         | 4.55%   |
| ECS                 | 1         | 4.55%   |
| Dell                | 1         | 4.55%   |
| Chuwi               | 1         | 4.55%   |
| ASUSTek Computer    | 1         | 4.55%   |
| ASRockRack          | 1         | 4.55%   |
| ASRock              | 1         | 4.55%   |
| Apple               | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung N150/N210/N220          | 1         | 4.55%   |
| Lenovo Yoga 710-11IKB 80V6      | 1         | 4.55%   |
| Lenovo ThinkPad X280 20KESB4T00 | 1         | 4.55%   |
| Lenovo ThinkPad X230 23255NG    | 1         | 4.55%   |
| Lenovo ThinkPad W520 42844DG    | 1         | 4.55%   |
| Lenovo ThinkPad T470 20HES0EV0A | 1         | 4.55%   |
| Lenovo ThinkPad E495 20NE000BSP | 1         | 4.55%   |
| Lenovo ThinkPad E14 20RA0036RT  | 1         | 4.55%   |
| Lenovo G50-70 20351             | 1         | 4.55%   |
| HP Z420 Workstation             | 1         | 4.55%   |
| HP EliteBook 750 G1             | 1         | 4.55%   |
| Fujitsu Siemens AMILO Li3710    | 1         | 4.55%   |
| Fujitsu CELSIUS H730            | 1         | 4.55%   |
| ECS Z77H2-AX                    | 1         | 4.55%   |
| Dell Latitude 7300              | 1         | 4.55%   |
| Chuwi CoreBook X                | 1         | 4.55%   |
| ASUS ROG STRIX B550-F GAMING    | 1         | 4.55%   |
| ASRockRack C226M WS             | 1         | 4.55%   |
| ASRock N68-S UCC                | 1         | 4.55%   |
| Apple MacBookPro14,1            | 1         | 4.55%   |
| Acer Swift SF314-56             | 1         | 4.55%   |
| Acer Aspire 7738                | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 27.27%  |
| Samsung N150          | 1         | 4.55%   |
| Lenovo Yoga           | 1         | 4.55%   |
| Lenovo G50-70         | 1         | 4.55%   |
| HP Z420               | 1         | 4.55%   |
| HP EliteBook          | 1         | 4.55%   |
| Fujitsu Siemens AMILO | 1         | 4.55%   |
| Fujitsu CELSIUS       | 1         | 4.55%   |
| ECS Z77H2-AX          | 1         | 4.55%   |
| Dell Latitude         | 1         | 4.55%   |
| Chuwi CoreBook        | 1         | 4.55%   |
| ASUS ROG              | 1         | 4.55%   |
| ASRockRack C226M      | 1         | 4.55%   |
| ASRock N68-S          | 1         | 4.55%   |
| Apple MacBookPro14    | 1         | 4.55%   |
| Acer Swift            | 1         | 4.55%   |
| Acer Aspire           | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 3         | 13.64%  |
| 2019 | 3         | 13.64%  |
| 2012 | 3         | 13.64%  |
| 2018 | 2         | 9.09%   |
| 2009 | 2         | 9.09%   |
| 2023 | 1         | 4.55%   |
| 2022 | 1         | 4.55%   |
| 2021 | 1         | 4.55%   |
| 2016 | 1         | 4.55%   |
| 2015 | 1         | 4.55%   |
| 2014 | 1         | 4.55%   |
| 2013 | 1         | 4.55%   |
| 2011 | 1         | 4.55%   |
| 2010 | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 17        | 77.27%  |
| Desktop  | 5         | 22.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 21        | 95.45%  |
| Yes  | 1         | 4.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 9         | 40.91%  |
| 16.01-24.0 | 6         | 27.27%  |
| 32.01-64.0 | 3         | 13.64%  |
| 2.01-3.0   | 2         | 9.09%   |
| 4.01-8.0   | 1         | 4.55%   |
| 24.01-32.0 | 1         | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 10        | 45.45%  |
| 0.51-1.0 | 7         | 31.82%  |
| 1.01-2.0 | 4         | 18.18%  |
| 2.01-3.0 | 1         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 14        | 63.64%  |
| 2      | 4         | 18.18%  |
| 0      | 2         | 9.09%   |
| 4      | 1         | 4.55%   |
| 3      | 1         | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 81.82%  |
| Yes       | 4         | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 77.27%  |
| No        | 5         | 22.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 81.82%  |
| No        | 4         | 18.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 59.09%  |
| No        | 9         | 40.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| France      | 5         | 22.73%  |
| USA         | 4         | 18.18%  |
| UK          | 4         | 18.18%  |
| Finland     | 2         | 9.09%   |
| Spain       | 1         | 4.55%   |
| San Marino  | 1         | 4.55%   |
| Russia      | 1         | 4.55%   |
| Netherlands | 1         | 4.55%   |
| Lithuania   | 1         | 4.55%   |
| Bulgaria    | 1         | 4.55%   |
| Argentina   | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Melun                | 2         | 9.09%   |
| Lutherville-Timonium | 2         | 9.09%   |
| West Bromwich        | 1         | 4.55%   |
| Wakefield            | 1         | 4.55%   |
| Vilnius              | 1         | 4.55%   |
| Vaasa                | 1         | 4.55%   |
| Urcuit               | 1         | 4.55%   |
| Turku                | 1         | 4.55%   |
| Sofia                | 1         | 4.55%   |
| Seattle              | 1         | 4.55%   |
| Sartrouville         | 1         | 4.55%   |
| San Marino           | 1         | 4.55%   |
| Saint-Raphaël       | 1         | 4.55%   |
| Rubí                | 1         | 4.55%   |
| Portland             | 1         | 4.55%   |
| Moscow               | 1         | 4.55%   |
| Lincoln              | 1         | 4.55%   |
| Eindhoven            | 1         | 4.55%   |
| Córdoba             | 1         | 4.55%   |
| Addlestone           | 1         | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 14.81%  |
| Samsung Electronics | 4         | 5      | 14.81%  |
| WDC                 | 3         | 3      | 11.11%  |
| SanDisk             | 3         | 3      | 11.11%  |
| Kingston            | 2         | 3      | 7.41%   |
| Crucial             | 2         | 2      | 7.41%   |
| UMIS                | 1         | 1      | 3.7%    |
| SPCC                | 1         | 1      | 3.7%    |
| SK hynix            | 1         | 1      | 3.7%    |
| Phison              | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 2      | 3.7%    |
| Corsair             | 1         | 1      | 3.7%    |
| AirDisk             | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB       | 2         | 6.9%    |
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 3.45%   |
| WDC WD40EFAX-68JH4N0 4TB          | 1         | 3.45%   |
| WDC WD30EZRZ-00GXCB0 3TB          | 1         | 3.45%   |
| UMIS RPJTJ256MED1OWX 256GB        | 1         | 3.45%   |
| SPCC Solid State Disk 128GB       | 1         | 3.45%   |
| SK hynix HFM512GDHTNG-8710B 512GB | 1         | 3.45%   |
| Seagate ST9250315AS 250GB         | 1         | 3.45%   |
| Seagate ST9160314AS 160GB         | 1         | 3.45%   |
| Seagate ST310212A 10GB            | 1         | 3.45%   |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 3.45%   |
| SanDisk X400 M.2 2280 256GB       | 1         | 3.45%   |
| SanDisk SDSSDA240G 240GB          | 1         | 3.45%   |
| SanDisk pSSD 16GB                 | 1         | 3.45%   |
| Samsung SSD 970 EVO Plus 2TB      | 1         | 3.45%   |
| Samsung SSD 970 EVO Plus 1TB      | 1         | 3.45%   |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 3.45%   |
| Samsung SSD 850 EVO mSATA 1TB     | 1         | 3.45%   |
| Samsung SSD 850 EVO 2TB           | 1         | 3.45%   |
| Phison Sabrent Rocket nano 512GB  | 1         | 3.45%   |
| Kingston SA400M8240G 240GB        | 1         | 3.45%   |
| Intel SSDPEKKF256G8L 256GB        | 1         | 3.45%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 3.45%   |
| Crucial CT256MX100SSD1 256GB      | 1         | 3.45%   |
| Crucial CT2000BX500SSD1 2TB       | 1         | 3.45%   |
| Corsair MP600 GS 1TB              | 1         | 3.45%   |
| AirDisk 512GB SSD                 | 1         | 3.45%   |
| A-DATA SSD DP900 512GB-DL3        | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| WDC     | 3         | 3      | 37.5%   |
| Hitachi | 1         | 2      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 25%     |
| Samsung Electronics | 3         | 3      | 25%     |
| Kingston            | 2         | 3      | 16.67%  |
| Crucial             | 2         | 2      | 16.67%  |
| SPCC                | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 12        | 13     | 50%     |
| NVMe | 6         | 8      | 25%     |
| HDD  | 6         | 9      | 25%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 22     | 72.73%  |
| NVMe | 6         | 8      | 27.27%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 14     | 57.89%  |
| 0.51-1.0   | 4         | 4      | 21.05%  |
| 1.01-2.0   | 2         | 2      | 10.53%  |
| 3.01-4.0   | 1         | 1      | 5.26%   |
| 2.01-3.0   | 1         | 1      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 12        | 54.55%  |
| 101-250    | 4         | 18.18%  |
| 21-50      | 3         | 13.64%  |
| 251-500    | 1         | 4.55%   |
| 501-1000   | 1         | 4.55%   |
| 51-100     | 1         | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 22        | 100%    |

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


| Model             | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| SanDisk pSSD 16GB | 1         | 1      | 100%    |

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
| Works   | 19        | 25     | 82.61%  |
| Malfunc | 3         | 4      | 13.04%  |
| Failed  | 1         | 1      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 18        | 66.67%  |
| Phison Electronics                      | 2         | 7.41%   |
| SK hynix                                | 1         | 3.7%    |
| Shenzhen Unionmemory Information System | 1         | 3.7%    |
| Samsung Electronics                     | 1         | 3.7%    |
| Nvidia                                  | 1         | 3.7%    |
| MAXIO Technology (Hangzhou)             | 1         | 3.7%    |
| ASMedia Technology                      | 1         | 3.7%    |
| AMD                                     | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 6.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 6.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 6.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 6.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 6.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 6.45%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 3.23%   |
| Shenzhen Unionmemory Information System AM611 PCIe 3.0 NVMe SSD 256GB          | 1         | 3.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 3.23%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1         | 3.23%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 3.23%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 3.23%   |
| Nvidia MCP61 IDE                                                               | 1         | 3.23%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 3.23%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 3.23%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 3.23%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1         | 3.23%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1         | 3.23%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                       | 1         | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 3.23%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 3.23%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 15        | 55.56%  |
| NVMe | 6         | 22.22%  |
| IDE  | 3         | 11.11%  |
| RAID | 2         | 7.41%   |
| SAS  | 1         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 19        | 86.36%  |
| AMD    | 3         | 13.64%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 4.55%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz           | 1         | 4.55%   |
| Intel CPU Version                             | 1         | 4.55%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 4.55%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 4.55%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 4.55%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 4.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 4.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4.55%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 4.55%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 4.55%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 4.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 4.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 4.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4.55%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 4.55%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 4.55%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 1         | 4.55%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 4.55%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1         | 4.55%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 4.55%   |
| AMD Phenom II X4 945 Processor                | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 36.36%  |
| Intel Core i7           | 4         | 18.18%  |
| Other                   | 2         | 9.09%   |
| Intel Xeon              | 2         | 9.09%   |
| AMD Ryzen 7             | 2         | 9.09%   |
| Intel Core i3           | 1         | 4.55%   |
| Intel Celeron Dual-Core | 1         | 4.55%   |
| Intel Atom              | 1         | 4.55%   |
| AMD Phenom II X4        | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 9         | 40.91%  |
| 2       | 8         | 36.36%  |
| 16      | 1         | 4.55%   |
| 12      | 1         | 4.55%   |
| 8       | 1         | 4.55%   |
| 6       | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 21        | 95.45%  |
| Unknown | 1         | 4.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 15        | 68.18%  |
| 1       | 6         | 27.27%  |
| Unknown | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 31.82%  |
| Haswell     | 4         | 18.18%  |
| IvyBridge   | 3         | 13.64%  |
| Penryn      | 2         | 9.09%   |
| Zen+        | 1         | 4.55%   |
| Zen 3       | 1         | 4.55%   |
| SandyBridge | 1         | 4.55%   |
| K10         | 1         | 4.55%   |
| Bonnell     | 1         | 4.55%   |
| Unknown     | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 17        | 68%     |
| Nvidia | 5         | 20%     |
| AMD    | 3         | 12%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 8%      |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 8%      |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 8%      |
| Nvidia GT216M [GeForce GT 240M]                                           | 1         | 4%      |
| Nvidia GP102 [TITAN X]                                                    | 1         | 4%      |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 4%      |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 4%      |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                   | 1         | 4%      |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller            | 1         | 4%      |
| Intel UHD Graphics 620                                                    | 1         | 4%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 4%      |
| Intel Iris Plus Graphics 640                                              | 1         | 4%      |
| Intel HD Graphics 620                                                     | 1         | 4%      |
| Intel HD Graphics 615                                                     | 1         | 4%      |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 4%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 4%      |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 1         | 4%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 4%      |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                           | 1         | 4%      |
| AMD Cape Verde GL [FirePro W4100]                                         | 1         | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 54.55%  |
| 1 x Nvidia     | 3         | 13.64%  |
| 1 x AMD        | 3         | 13.64%  |
| 2 x Intel      | 2         | 9.09%   |
| Intel + Nvidia | 2         | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 20        | 90.91%  |
| Proprietary | 2         | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 28.57%  |
| NEC Computers       | 1         | 14.29%  |
| Chimei Innolux      | 1         | 14.29%  |
| BOE                 | 1         | 14.29%  |
| AU Optronics        | 1         | 14.29%  |
| Apple               | 1         | 14.29%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch | 1         | 14.29%  |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 14.29%  |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch         | 1         | 14.29%  |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 260x140mm 11.6-inch     | 1         | 14.29%  |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                | 1         | 14.29%  |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch       | 1         | 14.29%  |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                | 1         | 14.29%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 4         | 57.14%  |
| 2880x1800       | 1         | 14.29%  |
| 2560x1440 (QHD) | 1         | 14.29%  |
| 1366x768 (WXGA) | 1         | 14.29%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 3         | 42.86%  |
| 13     | 2         | 28.57%  |
| 27     | 1         | 14.29%  |
| 11     | 1         | 14.29%  |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 4         | 57.14%  |
| 201-300     | 2         | 28.57%  |
| 501-600     | 1         | 14.29%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 6         | 85.71%  |
| 16/10 | 1         | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 2         | 28.57%  |
| 91-100         | 2         | 28.57%  |
| 51-60          | 1         | 14.29%  |
| 301-350        | 1         | 14.29%  |
| 101-110        | 1         | 14.29%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2         | 28.57%  |
| 101-120       | 2         | 28.57%  |
| More than 240 | 1         | 14.29%  |
| 161-240       | 1         | 14.29%  |
| 51-100        | 1         | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 17        | 77.27%  |
| 0     | 5         | 22.73%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 16        | 47.06%  |
| Realtek Semiconductor             | 7         | 20.59%  |
| Qualcomm Atheros                  | 3         | 8.82%   |
| Broadcom                          | 3         | 8.82%   |
| TP-Link                           | 1         | 2.94%   |
| Sierra Wireless                   | 1         | 2.94%   |
| Marvell Technology Group          | 1         | 2.94%   |
| Ericsson Business Mobile Networks | 1         | 2.94%   |
| Apple                             | 1         | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 4         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 4         | 9.52%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 4.76%   |
| Intel Ethernet Connection I217-LM                                           | 2         | 4.76%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 4.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 4.76%   |
| TP-Link Wireless USB Adapter                                                | 1         | 2.38%   |
| Sierra Wireless EM7305 Modem                                                | 1         | 2.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 1         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 2.38%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                          | 1         | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 2.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 2.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 2.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 2.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 1         | 2.38%   |
| Intel Wireless 8260                                                         | 1         | 2.38%   |
| Intel Wireless 7260                                                         | 1         | 2.38%   |
| Intel WiFi Link 5100                                                        | 1         | 2.38%   |
| Intel I210 Gigabit Network Connection                                       | 1         | 2.38%   |
| Intel Ethernet Controller I225-V                                            | 1         | 2.38%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-V                                        | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 2.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 2.38%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 2.38%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                             | 1         | 2.38%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                          | 1         | 2.38%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 2.38%   |
| Apple Ethernet Adapter [A1277]                                              | 1         | 2.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 52.38%  |
| Realtek Semiconductor | 4         | 19.05%  |
| Qualcomm Atheros      | 3         | 14.29%  |
| Broadcom              | 2         | 9.52%   |
| TP-Link               | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 2         | 9.52%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 9.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 9.52%   |
| TP-Link Wireless USB Adapter                                            | 1         | 4.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 4.76%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                      | 1         | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 4.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 4.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 4.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 4.76%   |
| Intel Wireless 8260                                                     | 1         | 4.76%   |
| Intel Wireless 7260                                                     | 1         | 4.76%   |
| Intel WiFi Link 5100                                                    | 1         | 4.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 4.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 4.76%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 4.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 10        | 55.56%  |
| Realtek Semiconductor    | 5         | 27.78%  |
| Marvell Technology Group | 1         | 5.56%   |
| Broadcom                 | 1         | 5.56%   |
| Apple                    | 1         | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 21.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 21.05%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 10.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 5.26%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 5.26%   |
| Intel I210 Gigabit Network Connection                             | 1         | 5.26%   |
| Intel Ethernet Controller I225-V                                  | 1         | 5.26%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.26%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 5.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 5.26%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 5.26%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 48.72%  |
| Ethernet | 18        | 46.15%  |
| Unknown  | 2         | 5.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 13        | 65%     |
| WiFi     | 7         | 35%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 12        | 54.55%  |
| 1     | 8         | 36.36%  |
| 3     | 1         | 4.55%   |
| 0     | 1         | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 20        | 90.91%  |
| Yes  | 2         | 9.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 53.85%  |
| Realtek Semiconductor           | 2         | 15.38%  |
| Broadcom                        | 2         | 15.38%  |
| Qualcomm Atheros Communications | 1         | 7.69%   |
| Cambridge Silicon Radio         | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 30.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 15.38%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 7.69%   |
| Realtek RTL8723B Bluetooth                          | 1         | 7.69%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)     | 1         | 7.69%   |
| Intel AX201 Bluetooth                               | 1         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.69%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 7.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 20        | 71.43%  |
| Nvidia                  | 3         | 10.71%  |
| AMD                     | 3         | 10.71%  |
| Creative Labs           | 1         | 3.57%   |
| BEHRINGER International | 1         | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 11.43%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 8.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 5.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 5.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 5.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 5.71%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 5.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 5.71%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 2.86%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.86%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 2.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.86%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.86%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 2.86%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.86%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 2.86%   |
| BEHRINGER International UMC 202HD 192k                                     | 1         | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 2.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 26.92%  |
| SK hynix            | 5         | 19.23%  |
| Kingston            | 5         | 19.23%  |
| Micron Technology   | 3         | 11.54%  |
| Unknown             | 3         | 11.54%  |
| Ramaxel Technology  | 1         | 3.85%   |
| Corsair             | 1         | 3.85%   |
| 48spaces            | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 3         | 10.71%  |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 3.57%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 3.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 3.57%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 3.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 3.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 3.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 3.57%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s                       | 1         | 3.57%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 3.57%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.57%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                              | 1         | 3.57%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s                        | 1         | 3.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 3.57%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s                       | 1         | 3.57%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2400MT/s                   | 1         | 3.57%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                   | 1         | 3.57%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s                     | 1         | 3.57%   |
| Kingston RAM 9905428-105.A00G 8GB SODIMM DDR3 1333MT/s                    | 1         | 3.57%   |
| Corsair RAM CMY16GX3M2A2133C11 8GB DIMM DDR3 1866MT/s                     | 1         | 3.57%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 9         | 39.13%  |
| DDR4   | 8         | 34.78%  |
| DDR2   | 3         | 13.04%  |
| LPDDR3 | 2         | 8.7%    |
| LPDDR5 | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 68.18%  |
| DIMM         | 5         | 22.73%  |
| Row Of Chips | 2         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 11        | 42.31%  |
| 4096  | 9         | 34.62%  |
| 2048  | 4         | 15.38%  |
| 16384 | 2         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 25%     |
| 2667  | 5         | 20.83%  |
| 2400  | 2         | 8.33%   |
| 6400  | 1         | 4.17%   |
| 3600  | 1         | 4.17%   |
| 2133  | 1         | 4.17%   |
| 1867  | 1         | 4.17%   |
| 1866  | 1         | 4.17%   |
| 1334  | 1         | 4.17%   |
| 1333  | 1         | 4.17%   |
| 1067  | 1         | 4.17%   |
| 667   | 1         | 4.17%   |
| 533   | 1         | 4.17%   |
| 400   | 1         | 4.17%   |

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
| Chicony Electronics           | 4         | 33.33%  |
| Realtek Semiconductor         | 2         | 16.67%  |
| Bison Electronics             | 2         | 16.67%  |
| Z-Star Microelectronics       | 1         | 8.33%   |
| Suyin                         | 1         | 8.33%   |
| Sunplus Innovation Technology | 1         | 8.33%   |
| IMC Networks                  | 1         | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Bison SunplusIT Integrated Camera        | 2         | 16.67%  |
| Z-Star Webcam                            | 1         | 8.33%   |
| Suyin HD Video WebCam                    | 1         | 8.33%   |
| Sunplus Hy HD Camera                     | 1         | 8.33%   |
| Realtek Lenovo EasyCamera                | 1         | 8.33%   |
| Realtek Integrated_Webcam_HD             | 1         | 8.33%   |
| IMC Networks EasyCamera                  | 1         | 8.33%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 8.33%   |
| Chicony Integrated Camera                | 1         | 8.33%   |
| Chicony HD WebCam                        | 1         | 8.33%   |
| Chicony FJ Camera                        | 1         | 8.33%   |

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
| 2     | 8         | 36.36%  |
| 1     | 6         | 27.27%  |
| 0     | 3         | 13.64%  |
| 4     | 2         | 9.09%   |
| 3     | 2         | 9.09%   |
| 7     | 1         | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 16        | 41.03%  |
| Bluetooth                | 7         | 17.95%  |
| Net/wireless             | 6         | 15.38%  |
| Fingerprint reader       | 4         | 10.26%  |
| Firewire controller      | 3         | 7.69%   |
| Card reader              | 2         | 5.13%   |
| Sound                    | 1         | 2.56%   |

