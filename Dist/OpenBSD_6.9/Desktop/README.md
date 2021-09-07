OpenBSD 6.9 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 6.9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=openbsd-6.9

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

| Vendor     | Model                   | Probe                                                     | Date         |
|------------|-------------------------|-----------------------------------------------------------|--------------|
| ASUSTek    | ROG STRIX B550-I GAMING | [1b6bf4666c](https://bsd-hardware.info/?probe=1b6bf4666c) | Sep 05, 2021 |
| Gigabyte   | GA-7VT600               | [83b86f3e8c](https://bsd-hardware.info/?probe=83b86f3e8c) | Aug 23, 2021 |
| Unknown    | FriendlyElec NanoPi R4S | [ac10928ac3](https://bsd-hardware.info/?probe=ac10928ac3) | Aug 05, 2021 |
| Unknown    | Pine64 Rock64           | [0df3f7572c](https://bsd-hardware.info/?probe=0df3f7572c) | Jul 23, 2021 |
| ASUSTek    | B202                    | [9f5f0a4117](https://bsd-hardware.info/?probe=9f5f0a4117) | Jul 21, 2021 |
| Unknown    | Pine64 Rock64           | [83c18360fc](https://bsd-hardware.info/?probe=83c18360fc) | Jul 12, 2021 |
| HP         | ProLiant DL360e Gen8    | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP         | ProLiant DL320 G5       | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn    | AT-7000 Series          | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| Unknown    | Pine64 Rock64           | [106c7823a8](https://bsd-hardware.info/?probe=106c7823a8) | Jul 10, 2021 |
| Unknown    | Pine64 Rock64           | [9cffa29c69](https://bsd-hardware.info/?probe=9cffa29c69) | Jul 08, 2021 |
| ASUSTek    | PRIME B560M-A           | [55f46bc85d](https://bsd-hardware.info/?probe=55f46bc85d) | Jul 07, 2021 |
| Dell       | 0GTK4K A02              | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| Supermicro | X8DTH-i/6/iF/6F         | [1e8ac47693](https://bsd-hardware.info/?probe=1e8ac47693) | Jun 08, 2021 |
| Supermicro | X8DTH-i/6/iF/6F         | [bd4a74c5e5](https://bsd-hardware.info/?probe=bd4a74c5e5) | Jun 08, 2021 |
| Supermicro | X10SLH-N6-ST031         | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| ASRock     | Z68 Extreme4 Gen3       | [58c8cdc060](https://bsd-hardware.info/?probe=58c8cdc060) | Jun 05, 2021 |
| Shuttle    | DS77U                   | [5d1c78145e](https://bsd-hardware.info/?probe=5d1c78145e) | May 30, 2021 |
| ASUSTek    | PRIME B560M-A           | [ca05acd52f](https://bsd-hardware.info/?probe=ca05acd52f) | May 30, 2021 |
| ASRock     | X570M Pro4              | [1d1a5afcfb](https://bsd-hardware.info/?probe=1d1a5afcfb) | May 28, 2021 |
| Alienware  | Aurora Ryzen Edition    | [b9dc8b182c](https://bsd-hardware.info/?probe=b9dc8b182c) | May 28, 2021 |
| ASUSTek    | B202                    | [0b66a5fd20](https://bsd-hardware.info/?probe=0b66a5fd20) | May 21, 2021 |
| PC Engines | APU2                    | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| Supermicro | X8STi                   | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| PC Engines | apu1                    | [7b4678c7ef](https://bsd-hardware.info/?probe=7b4678c7ef) | May 03, 2021 |
| ASUSTek    | P10S-I Series           | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| PC Engines | apu1                    | [c5ae3337e7](https://bsd-hardware.info/?probe=c5ae3337e7) | May 01, 2021 |
| HP         | ProLiant DL360 Gen9     | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| HP         | ProLiant DL360 Gen9     | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP         | EliteDesk 800 G5 SFF    | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 17       | 80.95%  |
| i386  | 2        | 9.52%   |
| arm64 | 2        | 9.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 11       | 52.38%  |
| fvwm    | 10       | 47.62%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 12       | 57.14%  |
| X11     | 9        | 42.86%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 20       | 95.24%  |
| SLiM    | 1        | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 85.71%  |
| en_US   | 2        | 9.52%   |
| ru_RU   | 1        | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 50%     |
| EFI  | 11       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 21       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 14       | 63.64%  |
| GPT  | 8        | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 19.05%  |
| ASUSTek Computer    | 4        | 19.05%  |
| Supermicro          | 3        | 14.29%  |
| PC Engines          | 2        | 9.52%   |
| ASRock              | 2        | 9.52%   |
| Unknown             | 2        | 9.52%   |
| Shuttle             | 1        | 4.76%   |
| Gigabyte Technology | 1        | 4.76%   |
| Foxconn             | 1        | 4.76%   |
| Alienware           | 1        | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 2        | 9.52%   |
| Supermicro X8STi               | 1        | 4.76%   |
| Supermicro X8DTH-i/6/iF/6F     | 1        | 4.76%   |
| Supermicro X10SLH-N6-ST031     | 1        | 4.76%   |
| Shuttle DS77U                  | 1        | 4.76%   |
| PC Engines APU2                | 1        | 4.76%   |
| PC Engines apu1                | 1        | 4.76%   |
| HP ProLiant DL360e Gen8        | 1        | 4.76%   |
| HP ProLiant DL360 Gen9         | 1        | 4.76%   |
| HP ProLiant DL320 G5           | 1        | 4.76%   |
| HP EliteDesk 800 G5 SFF        | 1        | 4.76%   |
| Gigabyte GA-7VT600             | 1        | 4.76%   |
| Foxconn AT-7000 Series         | 1        | 4.76%   |
| ASUS ROG STRIX B550-I GAMING   | 1        | 4.76%   |
| ASUS PRIME B560M-A             | 1        | 4.76%   |
| ASUS P10S-I Series             | 1        | 4.76%   |
| ASUS B202                      | 1        | 4.76%   |
| ASRock Z68 Extreme4 Gen3       | 1        | 4.76%   |
| ASRock X570M Pro4              | 1        | 4.76%   |
| Alienware Aurora Ryzen Edition | 1        | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| HP ProLiant                | 3        | 14.29%  |
| Unknown                    | 2        | 9.52%   |
| Supermicro X8STi           | 1        | 4.76%   |
| Supermicro X8DTH-i         | 1        | 4.76%   |
| Supermicro X10SLH-N6-ST031 | 1        | 4.76%   |
| Shuttle DS77U              | 1        | 4.76%   |
| PC Engines APU2            | 1        | 4.76%   |
| PC Engines apu1            | 1        | 4.76%   |
| HP EliteDesk               | 1        | 4.76%   |
| Gigabyte GA-7VT600         | 1        | 4.76%   |
| Foxconn AT-7000            | 1        | 4.76%   |
| ASUS ROG                   | 1        | 4.76%   |
| ASUS PRIME                 | 1        | 4.76%   |
| ASUS P10S-I                | 1        | 4.76%   |
| ASUS B202                  | 1        | 4.76%   |
| ASRock Z68                 | 1        | 4.76%   |
| ASRock X570M               | 1        | 4.76%   |
| Alienware Aurora           | 1        | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 4        | 19.05%  |
| 2020    | 3        | 14.29%  |
| 2019    | 2        | 9.52%   |
| 2018    | 2        | 9.52%   |
| 2012    | 2        | 9.52%   |
| 2008    | 2        | 9.52%   |
| Unknown | 2        | 9.52%   |
| 2017    | 1        | 4.76%   |
| 2014    | 1        | 4.76%   |
| 2010    | 1        | 4.76%   |
| 2003    | 1        | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 21       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 90.48%  |
| Yes  | 2        | 9.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 4        | 19.05%  |
| 32.01-64.0  | 4        | 19.05%  |
| 8.01-16.0   | 3        | 14.29%  |
| 24.01-32.0  | 2        | 9.52%   |
| 16.01-24.0  | 2        | 9.52%   |
| 1.01-2.0    | 2        | 9.52%   |
| 3.01-4.0    | 1        | 4.76%   |
| 2.01-3.0    | 1        | 4.76%   |
| 64.01-256.0 | 1        | 4.76%   |
| 0.51-1.0    | 1        | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 12       | 57.14%  |
| 0.51-1.0 | 5        | 23.81%  |
| 0        | 2        | 9.52%   |
| 4.01-8.0 | 1        | 4.76%   |
| 1.01-2.0 | 1        | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 31.82%  |
| 2      | 6        | 27.27%  |
| 3      | 3        | 13.64%  |
| 6      | 2        | 9.09%   |
| 4      | 2        | 9.09%   |
| 7      | 1        | 4.55%   |
| 5      | 1        | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 95.24%  |
| No        | 1        | 4.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 76.19%  |
| Yes       | 5        | 23.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 85.71%  |
| Yes       | 3        | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 5        | 23.81%  |
| Russia      | 4        | 19.05%  |
| Germany     | 4        | 19.05%  |
| France      | 3        | 14.29%  |
| Netherlands | 2        | 9.52%   |
| Ukraine     | 1        | 4.76%   |
| Taiwan      | 1        | 4.76%   |
| Spain       | 1        | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Moscow                | 4        | 19.05%  |
| Berlin                | 2        | 9.52%   |
| Van Nuys              | 1        | 4.76%   |
| Syeverodonets'k       | 1        | 4.76%   |
| Sedavi                | 1        | 4.76%   |
| Saint-Martin-d'Hères | 1        | 4.76%   |
| Roubaix               | 1        | 4.76%   |
| Plainfield            | 1        | 4.76%   |
| New York              | 1        | 4.76%   |
| New Taipei            | 1        | 4.76%   |
| Monts                 | 1        | 4.76%   |
| Independence          | 1        | 4.76%   |
| Heilbronn             | 1        | 4.76%   |
| Hamilton              | 1        | 4.76%   |
| Bielefeld             | 1        | 4.76%   |
| Barneveld             | 1        | 4.76%   |
| Amsterdam             | 1        | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| NVMe                | 5        | 6      | 13.89%  |
| Seagate             | 4        | 9      | 11.11%  |
| Samsung Electronics | 4        | 7      | 11.11%  |
| OPENBSD             | 3        | 3      | 8.33%   |
| HGST                | 3        | 4      | 8.33%   |
| WDC                 | 2        | 2      | 5.56%   |
| Intel               | 2        | 3      | 5.56%   |
| Hewlett-Packard     | 2        | 6      | 5.56%   |
| USB                 | 1        | 1      | 2.78%   |
| Transcend           | 1        | 4      | 2.78%   |
| Toshiba             | 1        | 1      | 2.78%   |
| SanDisk             | 1        | 1      | 2.78%   |
| Product:            | 1        | 1      | 2.78%   |
| Phison              | 1        | 1      | 2.78%   |
| Multiple            | 1        | 1      | 2.78%   |
| LSI                 | 1        | 1      | 2.78%   |
| Hitachi             | 1        | 1      | 2.78%   |
| Crucial             | 1        | 1      | 2.78%   |
| asmedia             | 1        | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| OPENBSD SR RAID 1 304GB          | 3        | 6.82%   |
| HGST HUS724020ALA640 2TB         | 2        | 4.55%   |
| WDC WD20PURX-64P6ZY0 2TB         | 1        | 2.27%   |
| WDC WD Elements 25A3 4TB         | 1        | 2.27%   |
| USB SanDisk 3.2Gen1 16GB         | 1        | 2.27%   |
| Transcend 3E128-TS2-550B01 100GB | 1        | 2.27%   |
| Toshiba DT01ACA100 1TB           | 1        | 2.27%   |
| Seagate ST950032 5AS 500GB       | 1        | 2.27%   |
| Seagate ST9160310AS 160GB        | 1        | 2.27%   |
| Seagate ST3808110AS 80GB         | 1        | 2.27%   |
| Seagate ST380011A 80GB           | 1        | 2.27%   |
| Seagate ST3160212ACE 160GB       | 1        | 2.27%   |
| Seagate ST2000LX001-1RG174 2TB   | 1        | 2.27%   |
| Seagate Backup+ SL 1TB           | 1        | 2.27%   |
| SanDisk Ultra 64GB               | 1        | 2.27%   |
| Samsung SSD 860 EVO M.2 2TB      | 1        | 2.27%   |
| Samsung SSD 860 EVO M.2 1TB      | 1        | 2.27%   |
| Samsung SSD 860 EVO 2TB          | 1        | 2.27%   |
| Samsung SSD 850 EVO 250GB        | 1        | 2.27%   |
| Samsung SSD 850 EVO 120GB        | 1        | 2.27%   |
| Samsung Flash Drive FIT 32GB     | 1        | 2.27%   |
| Product: Revision: 1100 18302PB  | 1        | 2.27%   |
| Phison SATA SSD 16GB             | 1        | 2.27%   |
| NVMe WDS100T1X0E-00AF 1TB        | 1        | 2.27%   |
| NVMe TOSHIBA-RC100 240GB         | 1        | 2.27%   |
| NVMe Samsung SSD 970 1TB         | 1        | 2.27%   |
| NVMe Samsung SSD 960 500GB       | 1        | 2.27%   |
| NVMe SAMSUNG MZVLB256 256GB      | 1        | 2.27%   |
| NVMe PC SN730 WD 512GB           | 1        | 2.27%   |
| Multiple Card Reader             | 1        | 2.27%   |
| LSI MR9271-8i 438GB              | 1        | 2.27%   |
| Intel SSDSC2BW240H6 240GB        | 1        | 2.27%   |
| Intel SSDSC2BB080G4 80GB         | 1        | 2.27%   |
| Hitachi HUA723020ALA640 2TB      | 1        | 2.27%   |
| HGST HTS541010A7E630 1TB         | 1        | 2.27%   |
| HP LOGICAL VOLUME 1TB            | 1        | 2.27%   |
| HP EG0300FCVBF 304GB             | 1        | 2.27%   |
| HP EG0300FCSPH 304GB             | 1        | 2.27%   |
| HP EG0300FBVFL 304GB             | 1        | 2.27%   |
| Crucial CT1000MX500SSD1 1TB      | 1        | 2.27%   |
| asmedia ASMT1051 240GB           | 1        | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 9      | 16.67%  |
| OPENBSD             | 3        | 3      | 12.5%   |
| NVMe                | 3        | 3      | 12.5%   |
| HGST                | 3        | 4      | 12.5%   |
| WDC                 | 2        | 2      | 8.33%   |
| Hewlett-Packard     | 2        | 6      | 8.33%   |
| USB                 | 1        | 1      | 4.17%   |
| Toshiba             | 1        | 1      | 4.17%   |
| Samsung Electronics | 1        | 1      | 4.17%   |
| Product:            | 1        | 1      | 4.17%   |
| Multiple            | 1        | 1      | 4.17%   |
| LSI                 | 1        | 1      | 4.17%   |
| Hitachi             | 1        | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 25%     |
| NVMe                | 2        | 2      | 16.67%  |
| Intel               | 2        | 3      | 16.67%  |
| Transcend           | 1        | 4      | 8.33%   |
| SanDisk             | 1        | 1      | 8.33%   |
| Phison              | 1        | 1      | 8.33%   |
| Crucial             | 1        | 1      | 8.33%   |
| asmedia             | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 34     | 58.33%  |
| SSD  | 9        | 19     | 37.5%   |
| NVMe | 1        | 1      | 4.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 20       | 53     | 95.24%  |
| NVMe | 1        | 1      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 15       | 33     | 57.69%  |
| 0.51-1.0        | 5        | 11     | 19.23%  |
| 1.01-2.0        | 4        | 7      | 15.38%  |
| More than 100.0 | 1        | 1      | 3.85%   |
| 3.01-4.0        | 1        | 1      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 28.57%  |
| More than 3000 | 4        | 19.05%  |
| 101-250        | 4        | 19.05%  |
| 1-20           | 3        | 14.29%  |
| 51-100         | 2        | 9.52%   |
| 21-50          | 1        | 4.76%   |
| 1001-2000      | 1        | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 11       | 50%     |
| 21-50     | 4        | 18.18%  |
| 101-250   | 2        | 9.09%   |
| 1001-2000 | 2        | 9.09%   |
| 251-500   | 1        | 4.55%   |
| 501-1000  | 1        | 4.55%   |
| 51-100    | 1        | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Transcend 3E128-TS2-550B01 100GB | 1        | 4      | 33.33%  |
| Seagate ST9160310AS 160GB        | 1        | 2      | 33.33%  |
| HGST HTS541010A7E630 1TB         | 1        | 2      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor    | Desktops | Drives | Percent |
|-----------|----------|--------|---------|
| Transcend | 1        | 4      | 33.33%  |
| Seagate   | 1        | 2      | 33.33%  |
| HGST      | 1        | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 2      | 50%     |
| HGST    | 1        | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 4      | 66.67%  |
| SSD  | 1        | 4      | 33.33%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 14       | 31     | 53.85%  |
| Detected | 9        | 15     | 34.62%  |
| Malfunc  | 3        | 8      | 11.54%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 12       | 41.38%  |
| AMD                      | 5        | 17.24%  |
| Samsung Electronics      | 3        | 10.34%  |
| Sandisk                  | 2        | 6.9%    |
| Hewlett-Packard          | 2        | 6.9%    |
| Broadcom / LSI           | 2        | 6.9%    |
| VIA Technologies         | 1        | 3.45%   |
| Toshiba                  | 1        | 3.45%   |
| Marvell Technology Group | 1        | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 6.06%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 2        | 6.06%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 3.03%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1        | 3.03%   |
| Sandisk WD Black SN850                                                                  | 1        | 3.03%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 3.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 3.03%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 3.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 3.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 3.03%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 3.03%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 3.03%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 3.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1        | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 3.03%   |
| HP Smart Array Gen9 Controllers                                                         | 1        | 3.03%   |
| HP Smart Array G6 controllers                                                           | 1        | 3.03%   |
| Broadcom / LSI SSS6200 PCI-Express Flash SSD                                            | 1        | 3.03%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 3.03%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1        | 3.03%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 3.03%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 13       | 46.43%  |
| NVMe | 5        | 17.86%  |
| IDE  | 5        | 17.86%  |
| RAID | 3        | 10.71%  |
| SAS  | 2        | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 61.9%   |
| AMD    | 6        | 28.57%  |
| ARM    | 2        | 9.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| ARM Cortex-A53 r0p4                                      | 2        | 9.52%   |
| Intel Xeon CPU X5675 @ 3.07GHz                           | 1        | 4.76%   |
| Intel Xeon CPU W3530 @ 2.80GHz                           | 1        | 4.76%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                      | 1        | 4.76%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz                       | 1        | 4.76%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz                      | 1        | 4.76%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                      | 1        | 4.76%   |
| Intel Core i5-9500 CPU @ 3.00GHz                         | 1        | 4.76%   |
| Intel Core i5-2500K CPU @ 3.30GHz                        | 1        | 4.76%   |
| Intel Core i3-3217U CPU @ 1.80GHz                        | 1        | 4.76%   |
| Intel Celeron D CPU 3.20GHz                              | 1        | 4.76%   |
| Intel Celeron CPU 3865U @ 1.80GHz                        | 1        | 4.76%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class) | 1        | 4.76%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz                  | 1        | 4.76%   |
| AMD Ryzen 7 5800X 8-Core Processor                       | 1        | 4.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics                   | 1        | 4.76%   |
| AMD Ryzen 7 3700X 8-Core Processor                       | 1        | 4.76%   |
| AMD GX-412TC SOC                                         | 1        | 4.76%   |
| AMD G-T40E Processor                                     | 1        | 4.76%   |
| AMD Athlon XP                                            | 1        | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Desktops | Percent |
|-----------------|----------|---------|
| Intel Xeon      | 6        | 28.57%  |
| AMD Ryzen 7     | 3        | 14.29%  |
| Intel Core i5   | 2        | 9.52%   |
| ARM Cortex      | 2        | 9.52%   |
| Other           | 1        | 4.76%   |
| Intel Core i3   | 1        | 4.76%   |
| Intel Celeron D | 1        | 4.76%   |
| Intel Celeron   | 1        | 4.76%   |
| Intel Atom      | 1        | 4.76%   |
| AMD GX          | 1        | 4.76%   |
| AMD G           | 1        | 4.76%   |
| AMD Athlon XP   | 1        | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 6        | 28.57%  |
| 6       | 4        | 19.05%  |
| 16      | 3        | 14.29%  |
| 2       | 3        | 14.29%  |
| Unknown | 3        | 14.29%  |
| 1       | 2        | 9.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 17       | 80.95%  |
| Unknown | 4        | 19.05%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 11       | 52.38%  |
| 2       | 6        | 28.57%  |
| Unknown | 4        | 19.05%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 3        | 14.29%  |
| Zen 3       | 2        | 9.52%   |
| SandyBridge | 2        | 9.52%   |
| KabyLake    | 2        | 9.52%   |
| Haswell     | 2        | 9.52%   |
| Zen 2       | 1        | 4.76%   |
| Westmere    | 1        | 4.76%   |
| Skylake     | 1        | 4.76%   |
| Puma        | 1        | 4.76%   |
| NetBurst    | 1        | 4.76%   |
| Nehalem     | 1        | 4.76%   |
| K6          | 1        | 4.76%   |
| IvyBridge   | 1        | 4.76%   |
| Bonnell     | 1        | 4.76%   |
| Bobcat      | 1        | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 6        | 33.33%  |
| Intel                      | 5        | 27.78%  |
| Matrox Electronics Systems | 4        | 22.22%  |
| ASPEED Technology          | 2        | 11.11%  |
| Nvidia                     | 1        | 5.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 2        | 10%     |
| Matrox Electronics Systems MGA G200EH                                         | 2        | 10%     |
| ASPEED Technology ASPEED Graphics Family                                      | 2        | 10%     |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2        | 10%     |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                        | 1        | 5%      |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1        | 5%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1        | 5%      |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                          | 1        | 5%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1        | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                              | 1        | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1        | 5%      |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                       | 1        | 5%      |
| AMD RV280 [Radeon 9200 PRO / 9250]                                            | 1        | 5%      |
| AMD ES1000                                                                    | 1        | 5%      |
| AMD Cezanne                                                                   | 1        | 5%      |
| AMD Caicos PRO [Radeon HD 7450]                                               | 1        | 5%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Other        | 4        | 19.05%  |
| 1 x Intel    | 4        | 19.05%  |
| 1 x AMD      | 4        | 19.05%  |
| 1 x Matrox   | 3        | 14.29%  |
| 1 x ASPEED   | 2        | 9.52%   |
| 2 x Intel    | 1        | 4.76%   |
| 2 x AMD      | 1        | 4.76%   |
| 1 x Nvidia   | 1        | 4.76%   |
| AMD + Matrox | 1        | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 13       | 61.9%   |
| Unknown | 8        | 38.1%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Vizio                | 1        | 14.29%  |
| Philips              | 1        | 14.29%  |
| Goldstar             | 1        | 14.29%  |
| Eizo                 | 1        | 14.29%  |
| Dell                 | 1        | 14.29%  |
| AOC                  | 1        | 14.29%  |
| Ancor Communications | 1        | 14.29%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                   | 1        | 14.29%  |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 1        | 14.29%  |
| Goldstar L1715S GSM436F 1280x1024 340x270mm 17.1-inch                 | 1        | 14.29%  |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                     | 1        | 14.29%  |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                     | 1        | 14.29%  |
| AOC 2270W AOC2270 1920x1080 480x270mm 21.7-inch                       | 1        | 14.29%  |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 1        | 14.29%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 3        | 42.86%  |
| 3840x2160 (4K)   | 1        | 14.29%  |
| 2560x1440 (QHD)  | 1        | 14.29%  |
| 1366x768 (WXGA)  | 1        | 14.29%  |
| 1280x1024 (SXGA) | 1        | 14.29%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 2        | 28.57%  |
| 31     | 1        | 14.29%  |
| 24     | 1        | 14.29%  |
| 23     | 1        | 14.29%  |
| 21     | 1        | 14.29%  |
| 17     | 1        | 14.29%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 57.14%  |
| 601-700     | 1        | 14.29%  |
| 401-500     | 1        | 14.29%  |
| 301-350     | 1        | 14.29%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 6        | 85.71%  |
| 5/4   | 1        | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 42.86%  |
| 301-350        | 2        | 28.57%  |
| 351-500        | 1        | 14.29%  |
| 141-150        | 1        | 14.29%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 3        | 42.86%  |
| 101-120 | 2        | 28.57%  |
| 1-50    | 1        | 14.29%  |
| 161-240 | 1        | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 14       | 66.67%  |
| 1     | 7        | 33.33%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 56%     |
| Realtek Semiconductor | 7        | 28%     |
| Broadcom              | 3        | 12%     |
| Ralink                | 1        | 4%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 13.79%  |
| Intel I210 Gigabit Network Connection                             | 3        | 10.34%  |
| Intel Wi-Fi 6 AX200                                               | 2        | 6.9%    |
| Intel I350 Gigabit Network Connection                             | 2        | 6.9%    |
| Intel I211 Gigabit Network Connection                             | 2        | 6.9%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 3.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 3.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 3.45%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 3.45%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.45%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 3.45%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 3.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 3.45%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.45%   |
| Intel Centrino Wireless-N 2200                                    | 1        | 3.45%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 3.45%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 3.45%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 3.45%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 3.45%   |
| Broadcom NetXtreme BCM5714 Gigabit Ethernet                       | 1        | 3.45%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 60%     |
| Realtek Semiconductor | 1        | 20%     |
| Ralink                | 1        | 20%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                        | 2        | 40%     |
| Realtek RTL8188EE Wireless Network Adapter | 1        | 20%     |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe  | 1        | 20%     |
| Intel Centrino Wireless-N 2200             | 1        | 20%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 59.09%  |
| Realtek Semiconductor | 6        | 27.27%  |
| Broadcom              | 3        | 13.64%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 16.67%  |
| Intel I210 Gigabit Network Connection                             | 3        | 12.5%   |
| Intel I350 Gigabit Network Connection                             | 2        | 8.33%   |
| Intel I211 Gigabit Network Connection                             | 2        | 8.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4.17%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 4.17%   |
| Intel Ethernet Controller I225-V                                  | 1        | 4.17%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 4.17%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 4.17%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 4.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 4.17%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 4.17%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 4.17%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 4.17%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 4.17%   |
| Broadcom NetXtreme BCM5714 Gigabit Ethernet                       | 1        | 4.17%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 80%     |
| WiFi     | 5        | 20%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 82.35%  |
| WiFi     | 3        | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 8        | 38.1%   |
| 1     | 5        | 23.81%  |
| 3     | 4        | 19.05%  |
| 12    | 1        | 4.76%   |
| 7     | 1        | 4.76%   |
| 4     | 1        | 4.76%   |
| 0     | 1        | 4.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 2        | 66.67%  |
| ASUSTek Computer | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Intel AX200 Bluetooth              | 2        | 66.67%  |
| ASUS Broadcom BCM20702A0 Bluetooth | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 6        | 40%     |
| AMD              | 5        | 33.33%  |
| VIA Technologies | 1        | 6.67%   |
| Nvidia           | 1        | 6.67%   |
| JMTek            | 1        | 6.67%   |
| Creative Labs    | 1        | 6.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 11.76%  |
| AMD Navi 10 HDMI Audio                                                            | 2        | 11.76%  |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1        | 5.88%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 5.88%   |
| JMTek USB PnP Audio Device                                                        | 1        | 5.88%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 5.88%   |
| Intel Sunrise Point-LP HD Audio                                                   | 1        | 5.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 5.88%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 5.88%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 1        | 5.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 5.88%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 1        | 5.88%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 5.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Unknown  | 2        | 66.67%  |
| Kingston | 1        | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s               | 1        | 16.67%  |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s         | 1        | 16.67%  |
| Unknown RAM Module 256MB DIMM 333MT/s               | 1        | 16.67%  |
| Unknown RAM Module 1GB DIMM 400MT/s                 | 1        | 16.67%  |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s | 1        | 16.67%  |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s   | 1        | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1        | 33.33%  |
| DDR3    | 1        | 33.33%  |
| Unknown | 1        | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 2        | 66.67%  |
| SODIMM | 1        | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 4096 | 2        | 33.33%  |
| 8192 | 1        | 16.67%  |
| 1024 | 1        | 16.67%  |
| 512  | 1        | 16.67%  |
| 256  | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 1        | 25%     |
| 1333  | 1        | 25%     |
| 400   | 1        | 25%     |
| 333   | 1        | 25%     |

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
| 0     | 9        | 42.86%  |
| 2     | 6        | 28.57%  |
| 1     | 6        | 28.57%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 41.18%  |
| Communication controller | 7        | 41.18%  |
| Storage/ata              | 1        | 5.88%   |
| Net/ethernet             | 1        | 5.88%   |
| Firewire controller      | 1        | 5.88%   |

