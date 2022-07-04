OpenBSD 7.1 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.1.

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

Total: 32

| Vendor     | Model                       | Probe                                                     | Date         |
|------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek    | TUF Gaming B550-PLUS        | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Gigabyte   | G41MT-S2                    | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| MSI        | MS-7C02                     | [65265eea62](https://bsd-hardware.info/?probe=65265eea62) | Jun 20, 2022 |
| Lenovo     | ThinkPad T530 24292VG       | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Apple      | MacPro4,1                   | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| ASUSTek    | PRIME H410M-E               | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| MSI        | MS-6788                     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown    | Raspberry Pi 3 Model B P... | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| Gigabyte   | H81M-S2PV                   | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| Biostar    | G31-M7 TE                   | [5c7af4b143](https://bsd-hardware.info/?probe=5c7af4b143) | May 21, 2022 |
| ASUSTek    | PRIME B550M-K               | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| MSI        | MS-7C82                     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| ASUSTek    | PRIME X470-PRO              | [9f6b4f114d](https://bsd-hardware.info/?probe=9f6b4f114d) | May 11, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [154799d7fa](https://bsd-hardware.info/?probe=154799d7fa) | May 08, 2022 |
| Intel      | Q3XXG4-P                    | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| MSI        | MS-7C37                     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| ASUSTek    | M4A88TD-V EVO/USB3          | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines | APU2                        | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Intel      | DH67BL                      | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA  | SH series                   | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo     | ThinkPad X240 20ALA0AHRT    | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Sony       | VPCL22Z1R                   | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| ASUSTek    | Z170-K                      | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek    | P10S-I Series               | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| Dell       | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Lenovo     | ThinkCentre M93p 10AAS25... | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo     | ThinkCentre M93p 10AAS25... | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Unknown    | LeMaker Banana Pi           | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 22       | 73.33%  |
| arm64 | 5        | 16.67%  |
| i386  | 2        | 6.67%   |
| armv7 | 1        | 3.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 25       | 83.33%  |
| XFCE         | 3        | 10%     |
| GNOME        | 1        | 3.33%   |
| Console      | 1        | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 17       | 56.67%  |
| Console | 13       | 43.33%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 30       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 83.33%  |
| ru_RU   | 4        | 13.33%  |
| C       | 1        | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 17       | 56.67%  |
| EFI  | 13       | 43.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 30       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 21       | 70%     |
| GPT  | 9        | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 7        | 23.33%  |
| Unknown             | 6        | 20%     |
| MSI                 | 4        | 13.33%  |
| Lenovo              | 3        | 10%     |
| Intel               | 2        | 6.67%   |
| Gigabyte Technology | 2        | 6.67%   |
| Sony                | 1        | 3.33%   |
| PC Engines          | 1        | 3.33%   |
| KOHJINSHA           | 1        | 3.33%   |
| Dell                | 1        | 3.33%   |
| Biostar             | 1        | 3.33%   |
| Apple               | 1        | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 6        | 20%     |
| Sony VPCL22Z1R                     | 1        | 3.33%   |
| PC Engines APU2                    | 1        | 3.33%   |
| MSI MS-7C82                        | 1        | 3.33%   |
| MSI MS-7C37                        | 1        | 3.33%   |
| MSI MS-7C02                        | 1        | 3.33%   |
| MSI MS-6788                        | 1        | 3.33%   |
| Lenovo ThinkPad X240 20ALA0AHRT    | 1        | 3.33%   |
| Lenovo ThinkPad T530 24292VG       | 1        | 3.33%   |
| Lenovo ThinkCentre M93p 10AAS25M00 | 1        | 3.33%   |
| KOHJINSHA SH series                | 1        | 3.33%   |
| Intel Q3XXG4-P                     | 1        | 3.33%   |
| Intel DH67BL                       | 1        | 3.33%   |
| Gigabyte H81M-S2PV                 | 1        | 3.33%   |
| Gigabyte G41MT-S2                  | 1        | 3.33%   |
| Dell G5 5090                       | 1        | 3.33%   |
| Biostar G31-M7 TE                  | 1        | 3.33%   |
| ASUS Z170-K                        | 1        | 3.33%   |
| ASUS TUF Gaming B550-PLUS          | 1        | 3.33%   |
| ASUS PRIME X470-PRO                | 1        | 3.33%   |
| ASUS PRIME H410M-E                 | 1        | 3.33%   |
| ASUS PRIME B550M-K                 | 1        | 3.33%   |
| ASUS P10S-I Series                 | 1        | 3.33%   |
| ASUS M4A88TD-V EVO/USB3            | 1        | 3.33%   |
| Apple MacPro4,1                    | 1        | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Unknown            | 6        | 20%     |
| ASUS PRIME         | 3        | 10%     |
| Lenovo ThinkPad    | 2        | 6.67%   |
| Sony VPCL22Z1R     | 1        | 3.33%   |
| PC Engines APU2    | 1        | 3.33%   |
| MSI MS-7C82        | 1        | 3.33%   |
| MSI MS-7C37        | 1        | 3.33%   |
| MSI MS-7C02        | 1        | 3.33%   |
| MSI MS-6788        | 1        | 3.33%   |
| Lenovo ThinkCentre | 1        | 3.33%   |
| KOHJINSHA SH       | 1        | 3.33%   |
| Intel Q3XXG4-P     | 1        | 3.33%   |
| Intel DH67BL       | 1        | 3.33%   |
| Gigabyte H81M-S2PV | 1        | 3.33%   |
| Gigabyte G41MT-S2  | 1        | 3.33%   |
| Dell G5            | 1        | 3.33%   |
| Biostar G31-M7     | 1        | 3.33%   |
| ASUS Z170-K        | 1        | 3.33%   |
| ASUS TUF           | 1        | 3.33%   |
| ASUS P10S-I        | 1        | 3.33%   |
| ASUS M4A88TD-V     | 1        | 3.33%   |
| Apple MacPro4      | 1        | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 23.33%  |
| 2020    | 4        | 13.33%  |
| 2018    | 3        | 10%     |
| 2010    | 3        | 10%     |
| 2022    | 2        | 6.67%   |
| 2021    | 2        | 6.67%   |
| 2019    | 2        | 6.67%   |
| 2016    | 2        | 6.67%   |
| 2015    | 1        | 3.33%   |
| 2014    | 1        | 3.33%   |
| 2011    | 1        | 3.33%   |
| 2009    | 1        | 3.33%   |
| 2007    | 1        | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 30       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 29       | 96.67%  |
| Yes  | 1        | 3.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 9        | 30%     |
| 16.01-24.0  | 6        | 20%     |
| 4.01-8.0    | 5        | 16.67%  |
| 3.01-4.0    | 2        | 6.67%   |
| 2.01-3.0    | 2        | 6.67%   |
| 1.01-2.0    | 2        | 6.67%   |
| 0.51-1.0    | 2        | 6.67%   |
| 24.01-32.0  | 1        | 3.33%   |
| 64.01-256.0 | 1        | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 26       | 86.67%  |
| 0        | 2        | 6.67%   |
| 4.01-8.0 | 1        | 3.33%   |
| 0.51-1.0 | 1        | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 60%     |
| 4      | 5        | 16.67%  |
| 3      | 3        | 10%     |
| 8      | 1        | 3.33%   |
| 6      | 1        | 3.33%   |
| 5      | 1        | 3.33%   |
| 2      | 1        | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 80%     |
| No        | 6        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 73.33%  |
| Yes       | 8        | 26.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 80%     |
| Yes       | 6        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 9        | 30%     |
| Netherlands | 4        | 13.33%  |
| USA         | 3        | 10%     |
| Italy       | 3        | 10%     |
| Germany     | 2        | 6.67%   |
| UK          | 1        | 3.33%   |
| Poland      | 1        | 3.33%   |
| Norway      | 1        | 3.33%   |
| Lithuania   | 1        | 3.33%   |
| India       | 1        | 3.33%   |
| Czechia     | 1        | 3.33%   |
| Canada      | 1        | 3.33%   |
| Austria     | 1        | 3.33%   |
| Argentina   | 1        | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Poortugaal       | 4        | 13.33%  |
| Vladivostok      | 3        | 10%     |
| Milan            | 2        | 6.67%   |
| Wolverhampton    | 1        | 3.33%   |
| Vienna           | 1        | 3.33%   |
| Tambov           | 1        | 3.33%   |
| St. Albert       | 1        | 3.33%   |
| Reutov           | 1        | 3.33%   |
| Oslo             | 1        | 3.33%   |
| Orenburg         | 1        | 3.33%   |
| Oakland          | 1        | 3.33%   |
| Nuremberg        | 1        | 3.33%   |
| Moscow           | 1        | 3.33%   |
| Memmingen        | 1        | 3.33%   |
| Krasnodar        | 1        | 3.33%   |
| Kolomna          | 1        | 3.33%   |
| Gianico          | 1        | 3.33%   |
| Gdansk           | 1        | 3.33%   |
| Delhi            | 1        | 3.33%   |
| Columbus         | 1        | 3.33%   |
| Český Těšín | 1        | 3.33%   |
| Buenos Aires     | 1        | 3.33%   |
| Brooklyn         | 1        | 3.33%   |
| Alytus           | 1        | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 16.33%  |
| Seagate             | 7        | 10     | 14.29%  |
| NVMe                | 7        | 9      | 14.29%  |
| Samsung Electronics | 6        | 11     | 12.24%  |
| Hitachi             | 3        | 4      | 6.12%   |
| Toshiba             | 2        | 4      | 4.08%   |
| OPENBSD             | 2        | 2      | 4.08%   |
| Crucial             | 2        | 2      | 4.08%   |
| Corsair             | 2        | 2      | 4.08%   |
| XPG                 | 1        | 1      | 2.04%   |
| StoreJet            | 1        | 1      | 2.04%   |
| SanDisk             | 1        | 1      | 2.04%   |
| OCZ                 | 1        | 1      | 2.04%   |
| Kingston            | 1        | 1      | 2.04%   |
| KingSpec            | 1        | 1      | 2.04%   |
| Intel               | 1        | 1      | 2.04%   |
| Hoodisk             | 1        | 1      | 2.04%   |
| HGST                | 1        | 1      | 2.04%   |
| Generic             | 1        | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB  | 2        | 3.85%   |
| OPENBSD SR RAID 1 752GB         | 2        | 3.85%   |
| NVMe Samsung SSD 980 1TB        | 2        | 3.85%   |
| XPG SX950U 240GB                | 1        | 1.92%   |
| WDC WD800JD-60LSA5 80GB         | 1        | 1.92%   |
| WDC WD6400AARS-00Y5B1 640GB     | 1        | 1.92%   |
| WDC WD5003AZEX-00K1GA0 500GB    | 1        | 1.92%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1        | 1.92%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1        | 1.92%   |
| WDC WD40EFZX-68AWUN0 4TB        | 1        | 1.92%   |
| WDC WD20PURX-64P6ZY0 2TB        | 1        | 1.92%   |
| WDC WD10EZEX-00MFCA0 1TB        | 1        | 1.92%   |
| Toshiba HDWG440 4TB             | 1        | 1.92%   |
| Toshiba DT01ACA050 500GB        | 1        | 1.92%   |
| StoreJet Transcend 120GB        | 1        | 1.92%   |
| Seagate ST3750640NS 752GB       | 1        | 1.92%   |
| Seagate ST3250318AS 250GB       | 1        | 1.92%   |
| Seagate ST3250310AS 250GB       | 1        | 1.92%   |
| Seagate ST250DM000-1BD141 250GB | 1        | 1.92%   |
| Seagate ST2000DM006-2DM164 2TB  | 1        | 1.92%   |
| Seagate ST1000VX000-1CU162 1TB  | 1        | 1.92%   |
| Seagate Expansion 320GB         | 1        | 1.92%   |
| SanDisk Extreme Pro 128GB       | 1        | 1.92%   |
| Samsung SSD 870 QVO 2TB         | 1        | 1.92%   |
| Samsung SSD 860 EVO 250GB       | 1        | 1.92%   |
| Samsung Portable SSD T3 250GB   | 1        | 1.92%   |
| Samsung HD753LJ 752GB           | 1        | 1.92%   |
| Samsung HD161HJ 160GB           | 1        | 1.92%   |
| Samsung Flash Drive FIT 32GB    | 1        | 1.92%   |
| OCZ VERTEX3 120GB               | 1        | 1.92%   |
| NVMe WDS100T3X0C-00SJ 1TB       | 1        | 1.92%   |
| NVMe WDC WDS500G2B0C- 500GB     | 1        | 1.92%   |
| NVMe TOSHIBA-RC100 240GB        | 1        | 1.92%   |
| NVMe Samsung SSD 970 250GB      | 1        | 1.92%   |
| NVMe PC SN520 WD 256GB          | 1        | 1.92%   |
| NVMe ADATA SX8200PNP 512GB      | 1        | 1.92%   |
| Kingston SMS200S330G 32GB       | 1        | 1.92%   |
| KingSpec NT-512 512GB           | 1        | 1.92%   |
| Intel SSDSC2BF180A4L 180GB      | 1        | 1.92%   |
| Hoodisk SSD 32GB                | 1        | 1.92%   |
| Hitachi HUA723020ALA640 2TB     | 1        | 1.92%   |
| Hitachi HTS541612J9AT00 120GB   | 1        | 1.92%   |
| Hitachi HDE721064SLA360 640GB   | 1        | 1.92%   |
| HGST HUS724020ALA640 2TB        | 1        | 1.92%   |
| Generic Flash Disk 2GB          | 1        | 1.92%   |
| Crucial CT2000MX500SSD1 2TB     | 1        | 1.92%   |
| Crucial CT1000MX500SSD1 1TB     | 1        | 1.92%   |
| Corsair Voyager SliderX1 32GB   | 1        | 1.92%   |
| Corsair FORCE LX SSD 256GB      | 1        | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 25.81%  |
| Seagate             | 7        | 10     | 22.58%  |
| Samsung Electronics | 3        | 3      | 9.68%   |
| NVMe                | 3        | 4      | 9.68%   |
| Hitachi             | 3        | 4      | 9.68%   |
| Toshiba             | 2        | 4      | 6.45%   |
| OPENBSD             | 2        | 2      | 6.45%   |
| StoreJet            | 1        | 1      | 3.23%   |
| HGST                | 1        | 1      | 3.23%   |
| Generic             | 1        | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 8      | 17.65%  |
| NVMe                | 3        | 4      | 17.65%  |
| Crucial             | 2        | 2      | 11.76%  |
| Corsair             | 2        | 2      | 11.76%  |
| XPG                 | 1        | 1      | 5.88%   |
| SanDisk             | 1        | 1      | 5.88%   |
| OCZ                 | 1        | 1      | 5.88%   |
| Kingston            | 1        | 1      | 5.88%   |
| KingSpec            | 1        | 1      | 5.88%   |
| Intel               | 1        | 1      | 5.88%   |
| Hoodisk             | 1        | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 39     | 51.72%  |
| SSD  | 13       | 23     | 44.83%  |
| NVMe | 1        | 1      | 3.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 62     | 96.43%  |
| NVMe | 1        | 1      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 28     | 51.28%  |
| 0.51-1.0   | 13       | 18     | 33.33%  |
| 1.01-2.0   | 4        | 11     | 10.26%  |
| 3.01-4.0   | 2        | 5      | 5.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 9        | 30%     |
| 251-500        | 6        | 20%     |
| 21-50          | 6        | 20%     |
| 1-20           | 3        | 10%     |
| 51-100         | 3        | 10%     |
| More than 3000 | 2        | 6.67%   |
| 501-1000       | 1        | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 27       | 90%     |
| 21-50     | 1        | 3.33%   |
| 2001-3000 | 1        | 3.33%   |
| 51-100    | 1        | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| XPG SX950U 240GB                  | 1        | 1      | 12.5%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 12.5%   |
| Seagate ST3750640NS 752GB         | 1        | 2      | 12.5%   |
| Seagate ST250DM000-1BD141 250GB   | 1        | 1      | 12.5%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 12.5%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 12.5%   |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 12.5%   |
| OCZ VERTEX3 120GB                 | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 4      | 37.5%   |
| Samsung Electronics | 2        | 2      | 25%     |
| XPG                 | 1        | 1      | 12.5%   |
| WDC                 | 1        | 1      | 12.5%   |
| OCZ                 | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 4      | 50%     |
| Samsung Electronics | 2        | 2      | 33.33%  |
| WDC                 | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 7      | 75%     |
| SSD  | 2        | 2      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 22       | 41     | 56.41%  |
| Detected | 9        | 12     | 23.08%  |
| Malfunc  | 7        | 9      | 17.95%  |
| Failed   | 1        | 1      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 17       | 50%     |
| AMD                      | 7        | 20.59%  |
| Samsung Electronics      | 3        | 8.82%   |
| SanDisk                  | 2        | 5.88%   |
| VIA Technologies         | 1        | 2.94%   |
| Toshiba                  | 1        | 2.94%   |
| Marvell Technology Group | 1        | 2.94%   |
| ASMedia Technology       | 1        | 2.94%   |
| ADATA Technology         | 1        | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 5.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 5.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 5.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 5.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 5.41%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 5.41%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 5.41%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 5.41%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 2.7%    |
| Toshiba BG3 NVMe SSD Controller                                                | 1        | 2.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 2.7%    |
| SanDisk unknown                                                                | 1        | 2.7%    |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.7%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 2.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.7%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 2.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1        | 2.7%    |
| Intel 82801EB (ICH5) SATA Controller                                           | 1        | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 2.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 62.5%   |
| NVMe | 7        | 21.88%  |
| IDE  | 5        | 15.63%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 56.67%  |
| AMD    | 7        | 23.33%  |
| ARM    | 6        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| ARM Cortex-A72 r0p3                                       | 4        | 13.33%  |
| Intel Xeon CPU E5520 @ 2.27GHz                            | 1        | 3.33%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1        | 3.33%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 1        | 3.33%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class)    | 1        | 3.33%   |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1        | 3.33%   |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1        | 3.33%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1        | 3.33%   |
| Intel Core i7-3610QM CPU @ 2.30GHz                        | 1        | 3.33%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1        | 3.33%   |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1        | 3.33%   |
| Intel Core i5-10400F CPU @ 2.90GHz                        | 1        | 3.33%   |
| Intel Core i3-5010U CPU @ 2.10GHz                         | 1        | 3.33%   |
| Intel Core i3-4010U CPU @ 1.70GHz                         | 1        | 3.33%   |
| Intel Core i3-3225 CPU @ 3.30GHz                          | 1        | 3.33%   |
| Intel Core i3-10100F CPU @ 3.60GHz                        | 1        | 3.33%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                     | 1        | 3.33%   |
| Intel Celeron CPU G1820 @ 2.70GHz                         | 1        | 3.33%   |
| ARM Cortex-A7 r0p4                                        | 1        | 3.33%   |
| ARM Cortex-A53 r0p4                                       | 1        | 3.33%   |
| AMD Ryzen 9 5950X 16-Core Processor                       | 1        | 3.33%   |
| AMD Ryzen 7 5800X 8-Core Processor                        | 1        | 3.33%   |
| AMD Ryzen 5 5600X 6-Core Processor                        | 1        | 3.33%   |
| AMD Ryzen 5 3600 6-Core Processor                         | 1        | 3.33%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics               | 1        | 3.33%   |
| AMD GX-412TC SOC                                          | 1        | 3.33%   |
| AMD Athlon II X4 640 Processor                            | 1        | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| ARM Cortex              | 6        | 20%     |
| Intel Core i7           | 4        | 13.33%  |
| Intel Core i3           | 4        | 13.33%  |
| Intel Xeon              | 2        | 6.67%   |
| Intel Core i5           | 2        | 6.67%   |
| AMD Ryzen 5             | 2        | 6.67%   |
| Intel Pentium Dual-Core | 1        | 3.33%   |
| Intel Pentium 4         | 1        | 3.33%   |
| Intel Genuine           | 1        | 3.33%   |
| Intel Core 2 Quad       | 1        | 3.33%   |
| Intel Celeron           | 1        | 3.33%   |
| AMD Ryzen 9             | 1        | 3.33%   |
| AMD Ryzen 7             | 1        | 3.33%   |
| AMD Ryzen 3             | 1        | 3.33%   |
| AMD GX                  | 1        | 3.33%   |
| AMD Athlon II X4        | 1        | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 33.33%  |
| 4       | 8        | 26.67%  |
| 2       | 5        | 16.67%  |
| 1       | 3        | 10%     |
| 8       | 2        | 6.67%   |
| 32      | 1        | 3.33%   |
| 12      | 1        | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 16       | 53.33%  |
| Unknown | 13       | 43.33%  |
| 2       | 1        | 3.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 43.33%  |
| 2       | 9        | 30%     |
| 1       | 8        | 26.67%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 8        | 26.67%  |
| Haswell     | 3        | 10%     |
| Zen 3       | 2        | 6.67%   |
| Skylake     | 2        | 6.67%   |
| Penryn      | 2        | 6.67%   |
| IvyBridge   | 2        | 6.67%   |
| Zen 2       | 1        | 3.33%   |
| Zen         | 1        | 3.33%   |
| SandyBridge | 1        | 3.33%   |
| Puma        | 1        | 3.33%   |
| P6          | 1        | 3.33%   |
| NetBurst    | 1        | 3.33%   |
| Nehalem     | 1        | 3.33%   |
| KabyLake    | 1        | 3.33%   |
| K10         | 1        | 3.33%   |
| CometLake   | 1        | 3.33%   |
| Broadwell   | 1        | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| AMD               | 11       | 45.83%  |
| Intel             | 7        | 29.17%  |
| Nvidia            | 5        | 20.83%  |
| ASPEED Technology | 1        | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2        | 8%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2        | 8%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2        | 8%      |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                            | 2        | 8%      |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                         | 1        | 4%      |
| Nvidia GK208B [GeForce GT 710]                                                | 1        | 4%      |
| Nvidia GF108M [NVS 5400M]                                                     | 1        | 4%      |
| Nvidia GF108M [GeForce GT 540M]                                               | 1        | 4%      |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1        | 4%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1        | 4%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1        | 4%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1        | 4%      |
| Intel HD Graphics 5500                                                        | 1        | 4%      |
| Intel HD Graphics 530                                                         | 1        | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1        | 4%      |
| ASPEED Technology ASPEED Graphics Family                                      | 1        | 4%      |
| AMD RV770 [Radeon HD 4850]                                                    | 1        | 4%      |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                  | 1        | 4%      |
| AMD RS880 [Radeon HD 4250]                                                    | 1        | 4%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1        | 4%      |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 1        | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x AMD     | 10       | 33.33%  |
| Other       | 7        | 23.33%  |
| 1 x Nvidia  | 5        | 16.67%  |
| 1 x Intel   | 5        | 16.67%  |
| 2 x Intel   | 1        | 3.33%   |
| Intel + AMD | 1        | 3.33%   |
| 1 x ASPEED  | 1        | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 19       | 63.33%  |
| Unknown | 11       | 36.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 3        | 23.08%  |
| Dell                 | 2        | 15.38%  |
| ViewSonic            | 1        | 7.69%   |
| Samsung Electronics  | 1        | 7.69%   |
| MSI                  | 1        | 7.69%   |
| Lenovo               | 1        | 7.69%   |
| InfoVision           | 1        | 7.69%   |
| Goldstar             | 1        | 7.69%   |
| Ancor Communications | 1        | 7.69%   |
| Acer                 | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 3        | 23.08%  |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1        | 7.69%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 7.69%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                      | 1        | 7.69%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 7.69%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1        | 7.69%   |
| Goldstar L1752T GSM4434 1280x1024 340x270mm 17.1-inch                  | 1        | 7.69%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                       | 1        | 7.69%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                      | 1        | 7.69%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 1        | 7.69%   |
| Acer XZ342CK ACR078B 3440x1440 800x330mm 34.1-inch                     | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 6        | 46.15%  |
| 1366x768 (WXGA)  | 2        | 15.38%  |
| 3840x2160 (4K)   | 1        | 7.69%   |
| 3440x1440        | 1        | 7.69%   |
| 1600x1200        | 1        | 7.69%   |
| 1440x900 (WXGA+) | 1        | 7.69%   |
| 1280x1024 (SXGA) | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 4        | 30.77%  |
| 54     | 1        | 7.69%   |
| 34     | 1        | 7.69%   |
| 24     | 1        | 7.69%   |
| 23     | 1        | 7.69%   |
| 20     | 1        | 7.69%   |
| 19     | 1        | 7.69%   |
| 18     | 1        | 7.69%   |
| 17     | 1        | 7.69%   |
| 12     | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 7        | 53.85%  |
| 501-600     | 2        | 15.38%  |
| 701-800     | 1        | 7.69%   |
| 301-350     | 1        | 7.69%   |
| 201-300     | 1        | 7.69%   |
| 1001-1500   | 1        | 7.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 9        | 69.23%  |
| 5/4   | 1        | 7.69%   |
| 4/3   | 1        | 7.69%   |
| 21/9  | 1        | 7.69%   |
| 16/10 | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 46.15%  |
| 151-200        | 2        | 15.38%  |
| 141-150        | 2        | 15.38%  |
| More than 1000 | 1        | 7.69%   |
| 61-70          | 1        | 7.69%   |
| 351-500        | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 6        | 50%     |
| 101-120 | 5        | 41.67%  |
| 121-160 | 1        | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 16       | 53.33%  |
| 1     | 13       | 43.33%  |
| 2     | 1        | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 14       | 42.42%  |
| Intel                             | 12       | 36.36%  |
| Qualcomm Atheros                  | 2        | 6.06%   |
| Qualcomm Atheros Communications   | 1        | 3.03%   |
| Qcom                              | 1        | 3.03%   |
| Ericsson Business Mobile Networks | 1        | 3.03%   |
| Broadcom                          | 1        | 3.03%   |
| AVM                               | 1        | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8        | 21.05%  |
| Intel 82574L Gigabit Network Connection                                       | 3        | 7.89%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 5.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 5.26%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 5.26%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 5.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 2.63%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 2.63%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 2.63%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 2.63%   |
| Qcom RT73 USB Wireless LAN Card                                               | 1        | 2.63%   |
| Intel Wireless 7260                                                           | 1        | 2.63%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 2.63%   |
| Intel Ethernet Connection I218-LM                                             | 1        | 2.63%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 2.63%   |
| Intel Centrino Advanced-N 6235                                                | 1        | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 2.63%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 2.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.63%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module            | 1        | 2.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 2.63%   |
| AVM A1 ISDN [Fritz]                                                           | 1        | 2.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 50%     |
| Qualcomm Atheros Communications | 1        | 12.5%   |
| Qualcomm Atheros                | 1        | 12.5%   |
| Qcom                            | 1        | 12.5%   |
| Broadcom                        | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                | 1        | 12.5%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 12.5%   |
| Qcom RT73 USB Wireless LAN Card                                | 1        | 12.5%   |
| Intel Wireless 7260                                            | 1        | 12.5%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 12.5%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 12.5%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 12.5%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 53.85%  |
| Intel                 | 11       | 42.31%  |
| Qualcomm Atheros      | 1        | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8        | 29.63%  |
| Intel 82574L Gigabit Network Connection                                       | 3        | 11.11%  |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 7.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 7.41%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 7.41%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 7.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 3.7%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 3.7%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 3.7%    |
| Intel Ethernet Connection I218-LM                                             | 1        | 3.7%    |
| Intel Ethernet Connection I217-LM                                             | 1        | 3.7%    |
| Intel 82579V Gigabit Network Connection                                       | 1        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 3.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 68.57%  |
| WiFi     | 8        | 22.86%  |
| Unknown  | 2        | 5.71%   |
| Modem    | 1        | 2.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 77.27%  |
| WiFi     | 5        | 22.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 36.67%  |
| 2     | 8        | 26.67%  |
| 0     | 6        | 20%     |
| 3     | 4        | 13.33%  |
| 4     | 1        | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 4        | 66.67%  |
| Foxconn / Hon Hai | 1        | 16.67%  |
| Apple             | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 16.67%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 1        | 16.67%  |
| Intel Bluetooth wireless interface                          | 1        | 16.67%  |
| Intel AX200 Bluetooth                                       | 1        | 16.67%  |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 16.67%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 14       | 45.16%  |
| AMD                 | 12       | 38.71%  |
| Nvidia              | 3        | 9.68%   |
| Creative Labs       | 1        | 3.23%   |
| C-Media Electronics | 1        | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 4        | 10%     |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 7.5%    |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 5%      |
| AMD Navi 10 HDMI Audio                                                            | 2        | 5%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 5%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 5%      |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 2.5%    |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 2.5%    |
| Intel Broadwell-U Audio Controller                                                | 1        | 2.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 2.5%    |
| Intel 8 Series HD Audio Controller                                                | 1        | 2.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 2.5%    |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 1        | 2.5%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 1        | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 2.5%    |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                        | 1        | 2.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1        | 2.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1        | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 2.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 1        | 2.5%    |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Kingston | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 32768 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 1        | 100%    |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Ricoh               | 1        | 50%     |
| Chicony Electronics | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Ricoh USB2.0 Camera                  | 1        | 50%     |
| Chicony Integrated Camera [ThinkPad] | 1        | 50%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 100%    |

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
| 0     | 13       | 43.33%  |
| 1     | 11       | 36.67%  |
| 2     | 4        | 13.33%  |
| 3     | 2        | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 12       | 48%     |
| Graphics card            | 5        | 20%     |
| Firewire controller      | 4        | 16%     |
| Storage                  | 1        | 4%      |
| Sound                    | 1        | 4%      |
| Network                  | 1        | 4%      |
| Net/wireless             | 1        | 4%      |

