OpenBSD 7.1 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.1/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.1/Notebook/README.md).

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

Total: 26

| Vendor     | Model                       | Form-Factor | Probe                                                     | Date         |
|------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Panasonic  | CF-52PFPBSFQ                | Notebook    | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| MSI        | MS-7C37                     | Desktop     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| MSI        | Modern 14 B11MOL            | Notebook    | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| ASUSTek    | M4A88TD-V EVO/USB3          | Desktop     | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines | APU2                        | Desktop     | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Intel      | DH67BL                      | Desktop     | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA  | SH series                   | Desktop     | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo     | ThinkPad X240 20ALA0AHRT    | Desktop     | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| DEXP       | NAVIS P100                  | Notebook    | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Sony       | VPCL22Z1R                   | Desktop     | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| Lenovo     | ThinkPad X121e 3053A52      | Notebook    | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| Samsung    | DP700A3D-X01RU SEC_SW_RE... | All in one  | [22febd212f](https://bsd-hardware.info/?probe=22febd212f) | Apr 22, 2022 |
| ASUSTek    | Z170-K                      | Desktop     | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek    | P10S-I Series               | Desktop     | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| TUXEDO     | Pulse 15 Gen1               | Notebook    | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Dell       | G5 5090                     | Desktop     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Lenovo     | ThinkPad X200 745969G       | Notebook    | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo     | ThinkCentre M93p 10AAS25... | Desktop     | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo     | ThinkCentre M93p 10AAS25... | Desktop     | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Lenovo     | ThinkPad X200 745969G       | Notebook    | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP         | Pavilion Laptop 15-cs0xx... | Notebook    | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| Lenovo     | Yoga 330-11IGM 81A6         | Notebook    | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Unknown    | LeMaker Banana Pi           | Desktop     | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Dell       | Vostro 3550                 | Notebook    | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Lenovo     | ThinkPad X200 745969G       | Notebook    | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Unknown    | Unknown                     | Desktop     | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 23        | 92%     |
| i386  | 1         | 4%      |
| armv7 | 1         | 4%      |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 17        | 68%     |
| fvwm         | 5         | 20%     |
| XFCE         | 2         | 8%      |
| Console      | 1         | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 19        | 76%     |
| Console | 6         | 24%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 25        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 17        | 68%     |
| ru_RU   | 8         | 32%     |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 14        | 56%     |
| BIOS | 11        | 44%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 25        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 16        | 64%     |
| GPT  | 9         | 36%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 28%     |
| ASUSTek Computer    | 3         | 12%     |
| MSI                 | 2         | 8%      |
| Dell                | 2         | 8%      |
| Unknown             | 2         | 8%      |
| TUXEDO              | 1         | 4%      |
| Sony                | 1         | 4%      |
| Samsung Electronics | 1         | 4%      |
| PC Engines          | 1         | 4%      |
| Panasonic           | 1         | 4%      |
| KOHJINSHA           | 1         | 4%      |
| Intel               | 1         | 4%      |
| Hewlett-Packard     | 1         | 4%      |
| DEXP                | 1         | 4%      |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G                | 3         | 12%     |
| Unknown                                     | 2         | 8%      |
| TUXEDO Pulse 15 Gen1                        | 1         | 4%      |
| Sony VPCL22Z1R                              | 1         | 4%      |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 4%      |
| PC Engines APU2                             | 1         | 4%      |
| Panasonic CF-52PFPBSFQ                      | 1         | 4%      |
| MSI MS-7C37                                 | 1         | 4%      |
| MSI Modern 14 B11MOL                        | 1         | 4%      |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 4%      |
| Lenovo ThinkPad X240 20ALA0AHRT             | 1         | 4%      |
| Lenovo ThinkPad X121e 3053A52               | 1         | 4%      |
| Lenovo ThinkCentre M93p 10AAS25M00          | 1         | 4%      |
| KOHJINSHA SH series                         | 1         | 4%      |
| Intel DH67BL                                | 1         | 4%      |
| HP Pavilion Laptop 15-cs0xxx                | 1         | 4%      |
| DEXP NAVIS P100                             | 1         | 4%      |
| Dell Vostro 3550                            | 1         | 4%      |
| Dell G5 5090                                | 1         | 4%      |
| ASUS Z170-K                                 | 1         | 4%      |
| ASUS P10S-I Series                          | 1         | 4%      |
| ASUS M4A88TD-V EVO/USB3                     | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 5         | 20%     |
| Unknown                | 2         | 8%      |
| TUXEDO Pulse           | 1         | 4%      |
| Sony VPCL22Z1R         | 1         | 4%      |
| Samsung DP700A3D       | 1         | 4%      |
| PC Engines APU2        | 1         | 4%      |
| Panasonic CF-52PFPBSFQ | 1         | 4%      |
| MSI MS-7C37            | 1         | 4%      |
| MSI Modern             | 1         | 4%      |
| Lenovo Yoga            | 1         | 4%      |
| Lenovo ThinkCentre     | 1         | 4%      |
| KOHJINSHA SH           | 1         | 4%      |
| Intel DH67BL           | 1         | 4%      |
| HP Pavilion            | 1         | 4%      |
| DEXP NAVIS             | 1         | 4%      |
| Dell Vostro            | 1         | 4%      |
| Dell G5                | 1         | 4%      |
| ASUS Z170-K            | 1         | 4%      |
| ASUS P10S-I            | 1         | 4%      |
| ASUS M4A88TD-V         | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 5         | 20%     |
| 2021    | 3         | 12%     |
| 2020    | 3         | 12%     |
| 2009    | 3         | 12%     |
| 2014    | 2         | 8%      |
| 2011    | 2         | 8%      |
| 2010    | 2         | 8%      |
| 2019    | 1         | 4%      |
| 2016    | 1         | 4%      |
| 2013    | 1         | 4%      |
| 2007    | 1         | 4%      |
| Unknown | 1         | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 13        | 52%     |
| Notebook   | 11        | 44%     |
| All in one | 1         | 4%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 24        | 96%     |
| Yes  | 1         | 4%      |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 9         | 36%     |
| 4.01-8.0   | 6         | 24%     |
| 16.01-24.0 | 5         | 20%     |
| 3.01-4.0   | 2         | 8%      |
| 2.01-3.0   | 2         | 8%      |
| 0.51-1.0   | 1         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 24        | 96%     |
| 0        | 1         | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 11        | 44%     |
| 2      | 8         | 32%     |
| 3      | 3         | 12%     |
| 4      | 2         | 8%      |
| 6      | 1         | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 84%     |
| No        | 4         | 16%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 76%     |
| No        | 6         | 24%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 68%     |
| No        | 8         | 32%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 11        | 44%     |
| Poland  | 4         | 16%     |
| USA     | 3         | 12%     |
| Canada  | 2         | 8%      |
| UK      | 1         | 4%      |
| Spain   | 1         | 4%      |
| Norway  | 1         | 4%      |
| Italy   | 1         | 4%      |
| Chile   | 1         | 4%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Vladivostok         | 6         | 24%     |
| Gdansk              | 3         | 12%     |
| West Valley City    | 1         | 4%      |
| Valdivia            | 1         | 4%      |
| Tambov              | 1         | 4%      |
| Starogard Gdański  | 1         | 4%      |
| St. Albert          | 1         | 4%      |
| Springboro          | 1         | 4%      |
| Reutov              | 1         | 4%      |
| Ozersk              | 1         | 4%      |
| Oslo                | 1         | 4%      |
| Newcastle upon Tyne | 1         | 4%      |
| Moscow              | 1         | 4%      |
| Montreal            | 1         | 4%      |
| Milan               | 1         | 4%      |
| Kolomna             | 1         | 4%      |
| Columbus            | 1         | 4%      |
| Alcorisa            | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 16.67%  |
| Samsung Electronics | 5         | 5      | 13.89%  |
| NVMe                | 5         | 6      | 13.89%  |
| WDC                 | 3         | 3      | 8.33%   |
| Innostor            | 3         | 3      | 8.33%   |
| OPENBSD             | 2         | 2      | 5.56%   |
| Kingston            | 2         | 2      | 5.56%   |
| Hitachi             | 2         | 2      | 5.56%   |
| HGST                | 2         | 2      | 5.56%   |
| XPG                 | 1         | 1      | 2.78%   |
| SanDisk             | 1         | 1      | 2.78%   |
| OCZ                 | 1         | 1      | 2.78%   |
| KingSpec            | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung HM321HI 320GB              | 3         | 8.11%   |
| Innostor SSD 15GB                  | 3         | 8.11%   |
| OPENBSD SR RAID 1 752GB            | 2         | 5.41%   |
| XPG SX950U 240GB                   | 1         | 2.7%    |
| WDC WD5003AZEX-00K1GA0 500GB       | 1         | 2.7%    |
| WDC WD20PURX-64P6ZY0 2TB           | 1         | 2.7%    |
| WDC WD10JPLX-00MBPT0 1TB           | 1         | 2.7%    |
| Seagate ST9500420AS 500GB          | 1         | 2.7%    |
| Seagate ST3750640NS 752GB          | 1         | 2.7%    |
| Seagate ST3250318AS 250GB          | 1         | 2.7%    |
| Seagate ST2000DM006-2DM164 2TB     | 1         | 2.7%    |
| Seagate ST1000VX000-1CU162 1TB     | 1         | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB     | 1         | 2.7%    |
| SanDisk Extreme 55AE 500GB         | 1         | 2.7%    |
| Samsung SSD 860 EVO 250GB          | 1         | 2.7%    |
| Samsung Flash Drive FIT 32GB       | 1         | 2.7%    |
| OCZ VERTEX3 120GB                  | 1         | 2.7%    |
| NVMe TOSHIBA-RC100 240GB           | 1         | 2.7%    |
| NVMe Samsung SSD 980 500GB         | 1         | 2.7%    |
| NVMe Samsung SSD 970 250GB         | 1         | 2.7%    |
| NVMe PC SN520 WD 256GB             | 1         | 2.7%    |
| NVMe KINGSTON OM8PDP3 256GB        | 1         | 2.7%    |
| Kingston SV300S37A120G 120GB       | 1         | 2.7%    |
| Kingston SMS200S330G 32GB          | 1         | 2.7%    |
| KingSpec NT-512 512GB              | 1         | 2.7%    |
| Intel SSDSC2BF180A4L 180GB         | 1         | 2.7%    |
| Hitachi HUA723020ALA640 2TB        | 1         | 2.7%    |
| Hitachi HTS541612J9AT00 120GB      | 1         | 2.7%    |
| HGST HUS724020ALA640 2TB           | 1         | 2.7%    |
| HGST HTS541010B7E610 1TB           | 1         | 2.7%    |
| Crucial CT2000MX500SSD1 2TB        | 1         | 2.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 28.57%  |
| Samsung Electronics | 4         | 4      | 19.05%  |
| WDC                 | 3         | 3      | 14.29%  |
| OPENBSD             | 2         | 2      | 9.52%   |
| NVMe                | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Innostor            | 3         | 3      | 21.43%  |
| NVMe                | 2         | 3      | 14.29%  |
| Kingston            | 2         | 2      | 14.29%  |
| XPG                 | 1         | 1      | 7.14%   |
| SanDisk             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| OCZ                 | 1         | 1      | 7.14%   |
| KingSpec            | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 23     | 53.85%  |
| SSD  | 11        | 15     | 42.31%  |
| NVMe | 1         | 1      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 38     | 95.65%  |
| NVMe | 1         | 1      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 23     | 59.26%  |
| 0.51-1.0   | 8         | 10     | 29.63%  |
| 1.01-2.0   | 3         | 5      | 11.11%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 8         | 32%     |
| 101-250        | 6         | 24%     |
| 1-20           | 5         | 20%     |
| 21-50          | 3         | 12%     |
| 51-100         | 2         | 8%      |
| More than 3000 | 1         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 23        | 92%     |
| 2001-3000 | 1         | 4%      |
| 101-250   | 1         | 4%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| XPG SX950U 240GB               | 1         | 1      | 20%     |
| Seagate ST9500420AS 500GB      | 1         | 1      | 20%     |
| Seagate ST3750640NS 752GB      | 1         | 2      | 20%     |
| Seagate ST2000DM006-2DM164 2TB | 1         | 1      | 20%     |
| OCZ VERTEX3 120GB              | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 60%     |
| XPG     | 1         | 1      | 20%     |
| OCZ     | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 60%     |
| SSD  | 2         | 2      | 40%     |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 17        | 24     | 62.96%  |
| Detected | 6         | 9      | 22.22%  |
| Malfunc  | 4         | 6      | 14.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 18        | 58.06%  |
| AMD                         | 5         | 16.13%  |
| Samsung Electronics         | 2         | 6.45%   |
| VIA Technologies            | 1         | 3.23%   |
| Toshiba                     | 1         | 3.23%   |
| Sandisk                     | 1         | 3.23%   |
| Marvell Technology Group    | 1         | 3.23%   |
| Kingston Technology Company | 1         | 3.23%   |
| ASMedia Technology          | 1         | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 9.38%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 9.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 6.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 6.25%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 3.13%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 3.13%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 3.13%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1         | 3.13%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 3.13%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 3.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 3.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 3.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 3.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1         | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 3.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 3.13%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 22        | 75.86%  |
| NVMe | 5         | 17.24%  |
| IDE  | 2         | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 18        | 72%     |
| AMD    | 5         | 20%     |
| ARM    | 1         | 4%      |
| 11th   | 1         | 4%      |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                      | 3         | 12%     |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1         | 4%      |
| Intel Pentium Silver N6000 @ 1.10GHz                      | 1         | 4%      |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                  | 1         | 4%      |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1         | 4%      |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1         | 4%      |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1         | 4%      |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1         | 4%      |
| Intel Core i5-8250U CPU @ 1.60GHz                         | 1         | 4%      |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1         | 4%      |
| Intel Core i5-3470T CPU @ 2.90GHz                         | 1         | 4%      |
| Intel Core i5-2520M CPU @ 2.50GHz                         | 1         | 4%      |
| Intel Core i5 CPU M 520 @ 2.40GHz                         | 1         | 4%      |
| Intel Core i3-4010U CPU @ 1.70GHz                         | 1         | 4%      |
| Intel Core i3-3225 CPU @ 3.30GHz                          | 1         | 4%      |
| Intel Celeron CPU N3350 @ 1.10GHz                         | 1         | 4%      |
| ARM Cortex-A7 r0p4                                        | 1         | 4%      |
| AMD Ryzen 7 5800X 8-Core Processor                        | 1         | 4%      |
| AMD Ryzen 7 4800H with Radeon Graphics                    | 1         | 4%      |
| AMD GX-412TC SOC                                          | 1         | 4%      |
| AMD E-300 APU with Radeon HD Graphics                     | 1         | 4%      |
| AMD Athlon II X4 640 Processor                            | 1         | 4%      |
| 11th Gen Intel Core i5-1135G7 @ 2.40GHz                   | 1         | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 5         | 20%     |
| Intel Core i7        | 3         | 12%     |
| Intel Core 2 Duo     | 3         | 12%     |
| Intel Pentium Silver | 2         | 8%      |
| Intel Core i3        | 2         | 8%      |
| AMD Ryzen 7          | 2         | 8%      |
| Other                | 1         | 4%      |
| Intel Xeon           | 1         | 4%      |
| Intel Genuine        | 1         | 4%      |
| Intel Celeron        | 1         | 4%      |
| ARM Cortex           | 1         | 4%      |
| AMD GX               | 1         | 4%      |
| AMD E                | 1         | 4%      |
| AMD Athlon II X4     | 1         | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 8         | 32%     |
| 2       | 8         | 32%     |
| Unknown | 5         | 20%     |
| 1       | 2         | 8%      |
| 16      | 1         | 4%      |
| 8       | 1         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 18        | 72%     |
| Unknown | 7         | 28%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 9         | 36%     |
| 1       | 9         | 36%     |
| Unknown | 7         | 28%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 4         | 16%     |
| Penryn        | 3         | 12%     |
| Skylake       | 2         | 8%      |
| SandyBridge   | 2         | 8%      |
| KabyLake      | 2         | 8%      |
| IvyBridge     | 2         | 8%      |
| Haswell       | 2         | 8%      |
| Zen 2         | 1         | 4%      |
| Westmere      | 1         | 4%      |
| Puma          | 1         | 4%      |
| P6            | 1         | 4%      |
| K10           | 1         | 4%      |
| Goldmont plus | 1         | 4%      |
| Goldmont      | 1         | 4%      |
| Bobcat        | 1         | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 15        | 62.5%   |
| AMD               | 7         | 29.17%  |
| Nvidia            | 1         | 4.17%   |
| ASPEED Technology | 1         | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 12%     |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 4%      |
| Intel UHD Graphics 620                                                        | 1         | 4%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 4%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 4%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 4%      |
| Intel JasperLake [UHD Graphics]                                               | 1         | 4%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1         | 4%      |
| Intel HD Graphics 530                                                         | 1         | 4%      |
| Intel HD Graphics 500                                                         | 1         | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 4%      |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 4%      |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 4%      |
| ASPEED Technology ASPEED Graphics Family                                      | 1         | 4%      |
| AMD Wrestler [Radeon HD 6310]                                                 | 1         | 4%      |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 1         | 4%      |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 4%      |
| AMD RS880 [Radeon HD 4250]                                                    | 1         | 4%      |
| AMD Renoir                                                                    | 1         | 4%      |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 1         | 4%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 1         | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| 1 x Intel   | 10        | 40%     |
| 1 x AMD     | 6         | 24%     |
| 2 x Intel   | 4         | 16%     |
| Other       | 2         | 8%      |
| 1 x Nvidia  | 1         | 4%      |
| Intel + AMD | 1         | 4%      |
| 1 x ASPEED  | 1         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 22        | 88%     |
| Unknown | 3         | 12%     |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 4         | 25%     |
| Lenovo                  | 3         | 18.75%  |
| Samsung Electronics     | 2         | 12.5%   |
| ViewSonic               | 1         | 6.25%   |
| Philips                 | 1         | 6.25%   |
| PANDA                   | 1         | 6.25%   |
| InfoVision              | 1         | 6.25%   |
| Chi Mei Optoelectronics | 1         | 6.25%   |
| AU Optronics            | 1         | 6.25%   |
| Acer                    | 1         | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 18.75%  |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch              | 1         | 6.25%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch   | 1         | 6.25%   |
| Samsung Electronics DM700A-D SEM0324 1920x1080 520x290mm 23.4-inch       | 1         | 6.25%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 1         | 6.25%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 6.25%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 6.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 6.25%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 1         | 6.25%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                    | 1         | 6.25%   |
| BOE LCD Monitor BOE07A5 1366x768 340x190mm 15.3-inch                     | 1         | 6.25%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 6.25%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 6.25%   |
| Acer XZ342CK ACR078B 3440x1440 800x330mm 34.1-inch                       | 1         | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 6         | 37.5%   |
| 1366x768 (WXGA) | 5         | 31.25%  |
| 1280x800 (WXGA) | 3         | 18.75%  |
| 3840x2160 (4K)  | 1         | 6.25%   |
| 3440x1440       | 1         | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 12     | 4         | 25%     |
| 15     | 3         | 18.75%  |
| 13     | 3         | 18.75%  |
| 21     | 2         | 12.5%   |
| 54     | 1         | 6.25%   |
| 34     | 1         | 6.25%   |
| 23     | 1         | 6.25%   |
| 11     | 1         | 6.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 6         | 37.5%   |
| 301-350     | 5         | 31.25%  |
| 401-500     | 2         | 12.5%   |
| 701-800     | 1         | 6.25%   |
| 501-600     | 1         | 6.25%   |
| 1001-1500   | 1         | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 12        | 75%     |
| 16/10 | 3         | 18.75%  |
| 21/9  | 1         | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 61-70          | 4         | 25%     |
| 201-250        | 3         | 18.75%  |
| 81-90          | 2         | 12.5%   |
| 91-100         | 2         | 12.5%   |
| More than 1000 | 1         | 6.25%   |
| 71-80          | 1         | 6.25%   |
| 51-60          | 1         | 6.25%   |
| 351-500        | 1         | 6.25%   |
| 101-110        | 1         | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 7         | 43.75%  |
| 101-120 | 5         | 31.25%  |
| 51-100  | 3         | 18.75%  |
| 161-240 | 1         | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 18        | 72%     |
| 0     | 7         | 28%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 18        | 47.37%  |
| Realtek Semiconductor             | 12        | 31.58%  |
| Qualcomm Atheros                  | 3         | 7.89%   |
| Qualcomm Atheros Communications   | 2         | 5.26%   |
| Qcom                              | 1         | 2.63%   |
| Ericsson Business Mobile Networks | 1         | 2.63%   |
| Dell                              | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 9         | 19.15%  |
| Intel Ultimate N WiFi Link 5300                                               | 3         | 6.38%   |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 6.38%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 4.26%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 4.26%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 4.26%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 4.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 2.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 2.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 2.13%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 2.13%   |
| Qcom RT73 USB Wireless LAN Card                                               | 1         | 2.13%   |
| Intel Wireless 7260                                                           | 1         | 2.13%   |
| Intel Wireless 3165                                                           | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 2.13%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 2.13%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 2.13%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 2.13%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 2.13%   |
| Intel Centrino Advanced-N 6200                                                | 1         | 2.13%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 2.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 2.13%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III   | 1         | 2.13%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                       | 1         | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 61.9%   |
| Realtek Semiconductor           | 2         | 9.52%   |
| Qualcomm Atheros Communications | 2         | 9.52%   |
| Qualcomm Atheros                | 2         | 9.52%   |
| Qcom                            | 1         | 4.76%   |
| Dell                            | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Ultimate N WiFi Link 5300                                | 3         | 14.29%  |
| Qualcomm Atheros AR9271 802.11n                                | 2         | 9.52%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 9.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 4.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 4.76%   |
| Qcom RT73 USB Wireless LAN Card                                | 1         | 4.76%   |
| Intel Wireless 7260                                            | 1         | 4.76%   |
| Intel Wireless 3165                                            | 1         | 4.76%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 4.76%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 4.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 4.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 4.76%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 4.76%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 4.76%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter        | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 11        | 47.83%  |
| Intel                 | 11        | 47.83%  |
| Qualcomm Atheros      | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 9         | 37.5%   |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 12.5%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 8.33%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 4.17%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 4.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 4.17%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 4.17%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 4.17%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 4.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 21        | 50%     |
| WiFi     | 19        | 45.24%  |
| Unknown  | 2         | 4.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 14        | 56%     |
| Ethernet | 11        | 44%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 16        | 64%     |
| 1     | 5         | 20%     |
| 3     | 3         | 12%     |
| 0     | 1         | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 58.82%  |
| Broadcom                        | 3         | 17.65%  |
| Realtek Semiconductor           | 1         | 5.88%   |
| Qualcomm Atheros Communications | 1         | 5.88%   |
| Foxconn / Hon Hai               | 1         | 5.88%   |
| Alps Electric                   | 1         | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 3         | 17.65%  |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 17.65%  |
| Intel AX200 Bluetooth                                       | 2         | 11.76%  |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 5.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 5.88%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 5.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 5.88%   |
| Intel AX201 Bluetooth                                       | 1         | 5.88%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 5.88%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 18        | 72%     |
| AMD    | 6         | 24%     |
| Nvidia | 1         | 4%      |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 9.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 9.68%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 6.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 3.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 3.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 3.23%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 3.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 3.23%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 3.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 3.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 3.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 3.23%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 3.23%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 3.23%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 3.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 3.23%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 3.23%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 3.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 1         | 25%     |
| SK Hynix          | 1         | 25%     |
| Kingston          | 1         | 25%     |
| A-DATA Technology | 1         | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 25%     |
| SK Hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s | 1         | 25%     |
| Kingston RAM 4143523531325836 4GB SODIMM DDR3 1333MT/s | 1         | 25%     |
| A-DATA RAM AM1U16BC4P2-B19C 4GB SODIMM DDR3 1600MT/s   | 1         | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR3 | 3         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 3         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 2         | 50%     |
| 2048 | 2         | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 1         | 33.33%  |
| 1333  | 1         | 33.33%  |
| 1067  | 1         | 33.33%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Ricoh                                  | 2         | 20%     |
| Chicony Electronics                    | 2         | 20%     |
| Acer                                   | 2         | 20%     |
| Silicon Motion                         | 1         | 10%     |
| Quanta                                 | 1         | 10%     |
| Denron                                 | 1         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 1         | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Silicon Motion WebCam SC-10IRQ12340N                                       | 1         | 10%     |
| Ricoh USB2.0 Camera                                                        | 1         | 10%     |
| Ricoh Integrated Webcam                                                    | 1         | 10%     |
| Quanta VGA WebCam                                                          | 1         | 10%     |
| Denron Corp., 2M Front Camera                                              | 1         | 10%     |
| Chicony Lenovo Integrated Camera UVC                                       | 1         | 10%     |
| Chicony HD Webcam                                                          | 1         | 10%     |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 10%     |
| Acer HD Webcam                                                             | 1         | 10%     |
| Acer EasyCamera                                                            | 1         | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader  | 1         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |

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
| 1     | 12        | 48%     |
| 2     | 7         | 28%     |
| 0     | 5         | 20%     |
| 3     | 1         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 16        | 57.14%  |
| Graphics card            | 5         | 17.86%  |
| Net/wireless             | 3         | 10.71%  |
| Firewire controller      | 3         | 10.71%  |
| Storage                  | 1         | 3.57%   |

