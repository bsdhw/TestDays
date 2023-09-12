NomadBSD 5806f915 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for NomadBSD 5806f915.

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

Total: 20

| Vendor   | Model                       | Probe                                                     | Date         |
|----------|-----------------------------|-----------------------------------------------------------|--------------|
| ASRock   | B550 Steel Legend           | [4e6381e037](https://bsd-hardware.info/?probe=4e6381e037) | Jun 22, 2022 |
| HP       | 2B29                        | [e8c355314e](https://bsd-hardware.info/?probe=e8c355314e) | Jun 17, 2022 |
| HP       | 1589                        | [3765f1cb09](https://bsd-hardware.info/?probe=3765f1cb09) | Jun 17, 2022 |
| ASUSTek  | Maximus VIII HERO           | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| MSI      | U-100 Ver.001               | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| Gigabyte | X570S GAMING X              | [ff39ace6ec](https://bsd-hardware.info/?probe=ff39ace6ec) | Feb 16, 2022 |
| Intel    | DCP847SKE                   | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| Dell     | 0M9KCM A01                  | [4db0a0ea05](https://bsd-hardware.info/?probe=4db0a0ea05) | Dec 06, 2021 |
| Gigabyte | MZGLKBP-00                  | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| ASUSTek  | PRIME Z390-P                | [1bd9270845](https://bsd-hardware.info/?probe=1bd9270845) | Nov 15, 2021 |
| Dell     | 0T10XW A01                  | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| Unknown  | X79                         | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| HP       | 87D6 SMVB                   | [f601f00e7c](https://bsd-hardware.info/?probe=f601f00e7c) | Oct 07, 2021 |
| Dell     | OptiPlex 3020               | [c391177240](https://bsd-hardware.info/?probe=c391177240) | Oct 05, 2021 |
| Dell     | OptiPlex 3020               | [070a0c6d62](https://bsd-hardware.info/?probe=070a0c6d62) | Sep 19, 2021 |
| Gigabyte | Z370 AORUS ULTRAGAMING W... | [13371b2ab8](https://bsd-hardware.info/?probe=13371b2ab8) | Jun 27, 2021 |
| ASUSTek  | ROG STRIX X299-E GAMING     | [e91dc55970](https://bsd-hardware.info/?probe=e91dc55970) | Jun 22, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [c6a1c1fa15](https://bsd-hardware.info/?probe=c6a1c1fa15) | May 25, 2021 |
| ASUSTek  | V-P7H55E                    | [8cf113ac55](https://bsd-hardware.info/?probe=8cf113ac55) | May 22, 2021 |
| Toshiba  | STI 005492G                 | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 18       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Openbox | 17       | 94.44%  |
| KDE5    | 1        | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 18       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 17       | 94.44%  |
| SDDM | 1        | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 8        | 44.44%  |
| ru_RU   | 2        | 11.11%  |
| pt_BR   | 2        | 11.11%  |
| de_DE   | 2        | 11.11%  |
| Unknown | 2        | 11.11%  |
| fi_FI   | 1        | 5.56%   |
| en_AU   | 1        | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 18       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 17       | 94.44%  |
| Zfs  | 1        | 5.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 18       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 5        | 27.78%  |
| Hewlett-Packard     | 3        | 16.67%  |
| Gigabyte Technology | 3        | 16.67%  |
| Dell                | 3        | 16.67%  |
| Semp Toshiba        | 1        | 5.56%   |
| Intel               | 1        | 5.56%   |
| ASRock              | 1        | 5.56%   |
| Unknown             | 1        | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Semp Toshiba STI                        | 1        | 5.56%   |
| Intel DCP847SKE                         | 1        | 5.56%   |
| HP Z420 Workstation                     | 1        | 5.56%   |
| HP Desktop M01-F1xxx                    | 1        | 5.56%   |
| HP 550-a114                             | 1        | 5.56%   |
| Gigabyte Z370 AORUS ULTRAGAMING WIFI-OP | 1        | 5.56%   |
| Gigabyte X570S GAMING X                 | 1        | 5.56%   |
| Gigabyte MZGLKBP-00                     | 1        | 5.56%   |
| Dell OptiPlex 9010                      | 1        | 5.56%   |
| Dell OptiPlex 3020                      | 1        | 5.56%   |
| Dell OptiPlex 3010                      | 1        | 5.56%   |
| ASUS V-P7H55E                           | 1        | 5.56%   |
| ASUS TUF GAMING B550M-PLUS              | 1        | 5.56%   |
| ASUS ROG STRIX X299-E GAMING            | 1        | 5.56%   |
| ASUS PRIME Z390-P                       | 1        | 5.56%   |
| ASUS Maximus VIII HERO                  | 1        | 5.56%   |
| ASRock B550 Steel Legend                | 1        | 5.56%   |
| Unknown                                 | 1        | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 3        | 16.67%  |
| Semp Toshiba STI    | 1        | 5.56%   |
| Intel DCP847SKE     | 1        | 5.56%   |
| HP Z420             | 1        | 5.56%   |
| HP Desktop          | 1        | 5.56%   |
| HP 550-a114         | 1        | 5.56%   |
| Gigabyte Z370       | 1        | 5.56%   |
| Gigabyte X570S      | 1        | 5.56%   |
| Gigabyte MZGLKBP-00 | 1        | 5.56%   |
| ASUS V-P7H55E       | 1        | 5.56%   |
| ASUS TUF            | 1        | 5.56%   |
| ASUS ROG            | 1        | 5.56%   |
| ASUS PRIME          | 1        | 5.56%   |
| ASUS Maximus        | 1        | 5.56%   |
| ASRock B550         | 1        | 5.56%   |
| Unknown             | 1        | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 4        | 22.22%  |
| 2019 | 4        | 22.22%  |
| 2015 | 3        | 16.67%  |
| 2013 | 2        | 11.11%  |
| 2022 | 1        | 5.56%   |
| 2020 | 1        | 5.56%   |
| 2018 | 1        | 5.56%   |
| 2010 | 1        | 5.56%   |
| 2009 | 1        | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 18       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 5        | 27.78%  |
| 32.01-64.0  | 4        | 22.22%  |
| 16.01-24.0  | 4        | 22.22%  |
| 64.01-256.0 | 3        | 16.67%  |
| 4.01-8.0    | 2        | 11.11%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 8        | 44.44%  |
| 0.01-0.5 | 6        | 33.33%  |
| 0.51-1.0 | 4        | 22.22%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 6        | 33.33%  |
| 2      | 5        | 27.78%  |
| 1      | 5        | 27.78%  |
| 4      | 2        | 11.11%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 55.56%  |
| Yes       | 8        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 94.44%  |
| No        | 1        | 5.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 72.22%  |
| No        | 5        | 27.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 52.63%  |
| Yes       | 9        | 47.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 7        | 38.89%  |
| Thailand  | 2        | 11.11%  |
| Russia    | 2        | 11.11%  |
| Germany   | 2        | 11.11%  |
| Brazil    | 2        | 11.11%  |
| Slovakia  | 1        | 5.56%   |
| Finland   | 1        | 5.56%   |
| Australia | 1        | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Volzhskiy      | 2        | 11.11%  |
| Rio de Janeiro | 2        | 11.11%  |
| Duncan         | 2        | 11.11%  |
| Bangkok        | 2        | 11.11%  |
| Tucson         | 1        | 5.56%   |
| Scottsdale     | 1        | 5.56%   |
| San Francisco  | 1        | 5.56%   |
| Palm Bay       | 1        | 5.56%   |
| Melcice        | 1        | 5.56%   |
| Marburg        | 1        | 5.56%   |
| Helsinki       | 1        | 5.56%   |
| Conway         | 1        | 5.56%   |
| Cologne        | 1        | 5.56%   |
| Brisbane       | 1        | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 19.44%  |
| Samsung Electronics | 6        | 8      | 16.67%  |
| Seagate             | 4        | 5      | 11.11%  |
| Crucial             | 4        | 4      | 11.11%  |
| Kingston            | 3        | 3      | 8.33%   |
| A-DATA Technology   | 3        | 3      | 8.33%   |
| Toshiba             | 2        | 3      | 5.56%   |
| SK hynix            | 2        | 2      | 5.56%   |
| Intel               | 2        | 2      | 5.56%   |
| Hewlett-Packard     | 2        | 2      | 5.56%   |
| Team                | 1        | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| WDC WDS100T1X0E-00AFY0 1TB                | 2        | 5%      |
| WDC WD40PURX-64GVNY0 4TB                  | 2        | 5%      |
| Kingston SA400S37480G 480GB               | 2        | 5%      |
| HP SSD EX950 2TB                          | 2        | 5%      |
| A-DATA SU630 240GB                        | 2        | 5%      |
| WDC WDS120G2G0A-00JH30 120GB              | 1        | 2.5%    |
| WDC WD60EZRZ-00GZ5B1 6TB                  | 1        | 2.5%    |
| WDC WD2500BEKT-00PVMT0 250GB              | 1        | 2.5%    |
| WDC WD10EADS-00P8B0 1TB                   | 1        | 2.5%    |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1        | 2.5%    |
| Toshiba MG06ACA800E 8TB                   | 1        | 2.5%    |
| Toshiba HDWD120 2TB                       | 1        | 2.5%    |
| Team TEAML5Lite3D1T 1TB                   | 1        | 2.5%    |
| SK hynix SKHynix_HFS256GD9TNI-L2B0B 256GB | 1        | 2.5%    |
| SK hynix SHGS31-500GS-2 500GB             | 1        | 2.5%    |
| Seagate ST9500325AS 500GB                 | 1        | 2.5%    |
| Seagate ST500DM002-1BD142 500GB           | 1        | 2.5%    |
| Seagate ST4000DM000-2AE166 4TB            | 1        | 2.5%    |
| Seagate ST3000DM008-2DM166 3TB            | 1        | 2.5%    |
| Samsung SSD 970 EVO 500GB                 | 1        | 2.5%    |
| Samsung SSD 970 EVO 2TB                   | 1        | 2.5%    |
| Samsung SSD 870 QVO 2TB                   | 1        | 2.5%    |
| Samsung SSD 870 EVO 1TB                   | 1        | 2.5%    |
| Samsung SSD 860 EVO 1TB                   | 1        | 2.5%    |
| Samsung SSD 840 EVO 250GB                 | 1        | 2.5%    |
| Samsung HM160HI 160GB                     | 1        | 2.5%    |
| Samsung HD161GJ 160GB                     | 1        | 2.5%    |
| Kingston SA2000M8500G 500GB               | 1        | 2.5%    |
| Intel SSDPEKNW020T8 2TB                   | 1        | 2.5%    |
| Intel MEMPEK1W032GA 32GB                  | 1        | 2.5%    |
| Crucial CT120BX300SSD1 120GB              | 1        | 2.5%    |
| Crucial CT1000P5SSD8 1TB                  | 1        | 2.5%    |
| Crucial CT1000P1SSD8 1TB                  | 1        | 2.5%    |
| Crucial CT1000MX500SSD1 1TB               | 1        | 2.5%    |
| A-DATA XM13 32GB                          | 1        | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 38.46%  |
| Seagate             | 4        | 5      | 30.77%  |
| Toshiba             | 2        | 3      | 15.38%  |
| Samsung Electronics | 2        | 2      | 15.38%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 23.08%  |
| A-DATA Technology   | 3        | 3      | 23.08%  |
| Kingston            | 2        | 2      | 15.38%  |
| Crucial             | 2        | 2      | 15.38%  |
| WDC                 | 1        | 1      | 7.69%   |
| Team                | 1        | 1      | 7.69%   |
| SK hynix            | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 10       | 14     | 34.48%  |
| HDD  | 10       | 15     | 34.48%  |
| NVMe | 9        | 13     | 31.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 16       | 29     | 64%     |
| NVMe | 9        | 13     | 36%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 10       | 15     | 45.45%  |
| 0.51-1.0   | 5        | 5      | 22.73%  |
| 3.01-4.0   | 3        | 3      | 13.64%  |
| 1.01-2.0   | 2        | 2      | 9.09%   |
| 2.01-3.0   | 1        | 1      | 4.55%   |
| 4.01-10.0  | 1        | 3      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 15       | 83.33%  |
| 101-250    | 2        | 11.11%  |
| 51-100     | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 17       | 94.44%  |
| 51-100  | 1        | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB          | 1        | 1      | 25%     |
| Toshiba HDWD120 2TB               | 1        | 1      | 25%     |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 25%     |
| A-DATA Technology XM13 32GB       | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Toshiba             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |
| A-DATA Technology   | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 33.33%  |
| Toshiba             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Works   | 17       | 38     | 85%     |
| Malfunc | 3        | 4      | 15%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 14       | 45.16%  |
| AMD                         | 5        | 16.13%  |
| SanDisk                     | 3        | 9.68%   |
| Samsung Electronics         | 2        | 6.45%   |
| Micron/Crucial Technology   | 2        | 6.45%   |
| Biwin Storage Technology    | 2        | 6.45%   |
| ASMedia Technology          | 2        | 6.45%   |
| Kingston Technology Company | 1        | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 8.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 5.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 5.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 5.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 5.71%   |
| Biwin Storage EX950 NVMe SSD                                                   | 2        | 5.71%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 5.71%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 5.71%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 2.86%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 1        | 2.86%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1        | 2.86%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 2.86%   |
| Intel SSD 660P Series                                                          | 1        | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.86%   |
| Intel NVMe Optane Memory Series                                                | 1        | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 2.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.86%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 2.86%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 2.86%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 55.17%  |
| NVMe | 9        | 31.03%  |
| IDE  | 2        | 6.9%    |
| RAID | 1        | 3.45%   |
| SAS  | 1        | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 72.22%  |
| AMD    | 5        | 27.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 11.11%  |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 5.56%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 5.56%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 5.56%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 5.56%   |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1        | 5.56%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 5.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 5.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 5.56%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 5.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 5.56%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 5.56%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 5.56%   |
| Intel Celeron CPU 847E @ 1.10GHz            | 1        | 5.56%   |
| AMD Ryzen 5 4600G with Radeon Graphics      | 1        | 5.56%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 1        | 5.56%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 1        | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 3        | 16.67%  |
| Intel Core i5           | 3        | 16.67%  |
| Intel Xeon              | 2        | 11.11%  |
| AMD Ryzen 9             | 2        | 11.11%  |
| AMD Ryzen 5             | 2        | 11.11%  |
| Intel Pentium Silver    | 1        | 5.56%   |
| Intel Pentium Dual-Core | 1        | 5.56%   |
| Intel Core i9           | 1        | 5.56%   |
| Intel Core i3           | 1        | 5.56%   |
| Intel Celeron           | 1        | 5.56%   |
| AMD A8                  | 1        | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 38.89%  |
| 2      | 3        | 16.67%  |
| 24     | 2        | 11.11%  |
| 12     | 2        | 11.11%  |
| 8      | 2        | 11.11%  |
| 16     | 1        | 5.56%   |
| 6      | 1        | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 66.67%  |
| 2      | 6        | 33.33%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 3        | 16.67%  |
| IvyBridge     | 3        | 16.67%  |
| Zen 3         | 2        | 11.11%  |
| Zen 2         | 2        | 11.11%  |
| SandyBridge   | 2        | 11.11%  |
| Skylake       | 1        | 5.56%   |
| Puma          | 1        | 5.56%   |
| Penryn        | 1        | 5.56%   |
| Nehalem       | 1        | 5.56%   |
| Haswell       | 1        | 5.56%   |
| Goldmont plus | 1        | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 7        | 36.84%  |
| Nvidia | 6        | 31.58%  |
| Intel  | 6        | 31.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2        | 10.53%  |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 2        | 10.53%  |
| Nvidia GT218 [GeForce 210]                                                | 1        | 5.26%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1        | 5.26%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 5.26%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                        | 1        | 5.26%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1        | 5.26%   |
| Nvidia GA104 [GeForce RTX 3070]                                           | 1        | 5.26%   |
| Intel HD Graphics 630                                                     | 1        | 5.26%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 1        | 5.26%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 5.26%   |
| AMD Vega 20 [Radeon VII]                                                  | 1        | 5.26%   |
| AMD Renoir                                                                | 1        | 5.26%   |
| AMD Pitcairn XT GL [FirePro W7000]                                        | 1        | 5.26%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 1        | 5.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 7        | 38.89%  |
| 1 x Nvidia     | 5        | 27.78%  |
| 1 x Intel      | 5        | 27.78%  |
| Intel + Nvidia | 1        | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 13       | 72.22%  |
| Proprietary | 4        | 22.22%  |
| Unknown     | 1        | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 77.78%  |
| 7.01-8.0   | 1        | 5.56%   |
| 5.01-6.0   | 1        | 5.56%   |
| 3.01-4.0   | 1        | 5.56%   |
| 0.01-0.5   | 1        | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 5        | 38.46%  |
| Samsung Electronics  | 2        | 15.38%  |
| ASUSTek Computer     | 2        | 15.38%  |
| Ancor Communications | 2        | 15.38%  |
| ___                  | 1        | 7.69%   |
| Westinghouse         | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch         | 2        | 15.38%  |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 7.69%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch         | 1        | 7.69%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch    | 1        | 7.69%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                    | 1        | 7.69%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 7.69%   |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch          | 1        | 7.69%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 1        | 7.69%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 7.69%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1        | 7.69%   |
| Ancor Communications PA248 ACI24B1 1920x1200 550x350mm 25.7-inch     | 1        | 7.69%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 7        | 58.33%  |
| 3840x2160 (4K)    | 2        | 16.67%  |
| 1920x1200 (WUXGA) | 1        | 8.33%   |
| 1366x768 (WXGA)   | 1        | 8.33%   |
| 1360x768          | 1        | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 4        | 30.77%  |
| 24      | 2        | 15.38%  |
| 18      | 2        | 15.38%  |
| Unknown | 2        | 15.38%  |
| 39      | 1        | 7.69%   |
| 27      | 1        | 7.69%   |
| 25      | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 6        | 50%     |
| 501-600     | 3        | 25%     |
| Unknown     | 2        | 16.67%  |
| 801-900     | 1        | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 83.33%  |
| 16/10   | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 46.15%  |
| 141-150        | 2        | 15.38%  |
| Unknown        | 2        | 15.38%  |
| 301-350        | 1        | 7.69%   |
| 251-300        | 1        | 7.69%   |
| 501-1000       | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 45.45%  |
| 101-120 | 3        | 27.27%  |
| Unknown | 2        | 18.18%  |
| 161-240 | 1        | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 55.56%  |
| 0     | 6        | 33.33%  |
| 2     | 2        | 11.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 46.43%  |
| Intel                 | 7        | 25%     |
| Broadcom              | 3        | 10.71%  |
| Ralink Technology     | 1        | 3.57%   |
| Qualcomm Atheros      | 1        | 3.57%   |
| Microchip Technology  | 1        | 3.57%   |
| Edimax Technology     | 1        | 3.57%   |
| D-Link System         | 1        | 3.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 7        | 21.88%  |
| Realtek RTL8125 2.5GbE Controller                                    | 3        | 9.38%   |
| Intel Ethernet Connection (2) I219-V                                 | 3        | 9.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2        | 6.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1        | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 3.13%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 3.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1        | 3.13%   |
| Ralink RT5372 Wireless Adapter                                       | 1        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 3.13%   |
| Microchip MCP2200 USB-to-Serial Port                                 | 1        | 3.13%   |
| Intel Wireless 8265 / 8275                                           | 1        | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 3.13%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 3.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 1        | 3.13%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 3.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 3.13%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 1        | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1        | 3.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 35.71%  |
| Broadcom              | 3        | 21.43%  |
| Intel                 | 2        | 14.29%  |
| Ralink Technology     | 1        | 7.14%   |
| Qualcomm Atheros      | 1        | 7.14%   |
| Edimax Technology     | 1        | 7.14%   |
| D-Link System         | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1        | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 7.14%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 7.14%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 7.14%   |
| Ralink RT5372 Wireless Adapter                                       | 1        | 7.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 7.14%   |
| Intel Wireless 8265 / 8275                                           | 1        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 7.14%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 1        | 7.14%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 7.14%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 7.14%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 1        | 7.14%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 64.71%  |
| Intel                 | 6        | 35.29%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 41.18%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 17.65%  |
| Intel Ethernet Connection (2) I219-V                              | 3        | 17.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 11.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 5.88%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 54.84%  |
| WiFi     | 13       | 41.94%  |
| Modem    | 1        | 3.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 66.67%  |
| WiFi     | 7        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 55.56%  |
| 2     | 8        | 44.44%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 88.89%  |
| Yes  | 2        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 2        | 22.22%  |
| Broadcom                        | 2        | 22.22%  |
| Realtek Semiconductor           | 1        | 11.11%  |
| Qualcomm Atheros Communications | 1        | 11.11%  |
| Cambridge Silicon Radio         | 1        | 11.11%  |
| ASUSTek Computer                | 1        | 11.11%  |
| Apple                           | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 11.11%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 11.11%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 11.11%  |
| Intel Bluetooth wireless interface                  | 1        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 11.11%  |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 11.11%  |
| Broadcom BCM2045 Bluetooth                          | 1        | 11.11%  |
| ASUS Bluetooth Controller                           | 1        | 11.11%  |
| Apple Bluetooth Host Controller                     | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 13       | 36.11%  |
| AMD                 | 8        | 22.22%  |
| Nvidia              | 6        | 16.67%  |
| Sony                | 2        | 5.56%   |
| XMOS                | 1        | 2.78%   |
| Quanta              | 1        | 2.78%   |
| LG Electronics      | 1        | 2.78%   |
| Creative Technology | 1        | 2.78%   |
| Corsair             | 1        | 2.78%   |
| C-Media Electronics | 1        | 2.78%   |
| Audio-Technica      | 1        | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 7.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 7.14%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 4.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 4.76%   |
| XMOS Shanling UA2                                                          | 1        | 2.38%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 2.38%   |
| Sony Audio                                                                 | 1        | 2.38%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                           | 1        | 2.38%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.38%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.38%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 2.38%   |
| LG Electronics USB Audio LG UltraFine Display Audio                        | 1        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.38%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.38%   |
| Creative Technology Sound Blaster Omni Surround 5.1                        | 1        | 2.38%   |
| Corsair VOID PRO Wireless Gaming Headset                                   | 1        | 2.38%   |
| Corsair ST100 Headset Output                                               | 1        | 2.38%   |
| C-Media Electronics Audio Device                                           | 1        | 2.38%   |
| Audio-Technica AT2020USB+ Audio Control                                    | 1        | 2.38%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 2.38%   |
| AMD FCH Azalia Controller                                                  | 1        | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 20%     |
| Kingston            | 4        | 20%     |
| SK hynix            | 2        | 10%     |
| Samsung Electronics | 2        | 10%     |
| Micron Technology   | 2        | 10%     |
| G.Skill             | 2        | 10%     |
| Corsair             | 2        | 10%     |
| Nanya Technology    | 1        | 5%      |
| Crucial             | 1        | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 9.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 4.76%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1        | 4.76%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 4.76%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s            | 1        | 4.76%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 4.76%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 4.76%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s  | 1        | 4.76%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 4.76%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s     | 1        | 4.76%   |
| Micron RAM 36JSZF1G72PZ-1G4D 8GB DIMM DDR3 1333MT/s    | 1        | 4.76%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1600MT/s        | 1        | 4.76%   |
| Kingston RAM K531R8-ETB 4GB DIMM DDR3 1600MT/s         | 1        | 4.76%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s | 1        | 4.76%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s | 1        | 4.76%   |
| G.Skill RAM F4-3600C17-16GTZSW 16GB DIMM DDR4 3600MT/s | 1        | 4.76%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s    | 1        | 4.76%   |
| Crucial RAM BLS8G4D240FSB.16FBD 8GB DIMM DDR4 2933MT/s | 1        | 4.76%   |
| Corsair RAM Module 8GB DIMM DDR4 3200MT/s              | 1        | 4.76%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3200MT/s | 1        | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 9        | 50%     |
| DDR3  | 7        | 38.89%  |
| SDRAM | 1        | 5.56%   |
| DDR   | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 88.89%  |
| SODIMM | 2        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 38.89%  |
| 4096  | 5        | 27.78%  |
| 16384 | 4        | 22.22%  |
| 2048  | 2        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 5        | 27.78%  |
| 1600    | 5        | 27.78%  |
| 1333    | 3        | 16.67%  |
| 3600    | 1        | 5.56%   |
| 2933    | 1        | 5.56%   |
| 2667    | 1        | 5.56%   |
| 2400    | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| HP PNP Fax Null                                                          | 1        | 50%     |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1        | 50%     |

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


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Quanta | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Quanta Realtek DMFT RGB | 1        | 100%    |

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
| 1     | 9        | 50%     |
| 2     | 6        | 33.33%  |
| 0     | 2        | 11.11%  |
| 3     | 1        | 5.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 11       | 45.83%  |
| Net/wireless             | 6        | 25%     |
| Firewire controller      | 3        | 12.5%   |
| Network                  | 2        | 8.33%   |
| Sound                    | 1        | 4.17%   |
| Bluetooth                | 1        | 4.17%   |

