pfSense - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for pfSense.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/pfSense/Desktop/README.md) and [notebooks](/Dist/pfSense/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Intel         | Q3XXG4-P V1.0               | Desktop     | [8bbeb73a52](https://bsd-hardware.info/?probe=8bbeb73a52) | Jan 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [98ed242ae0](https://bsd-hardware.info/?probe=98ed242ae0) | Jan 01, 2022 |
| Dell          | 06D7TR A02                  | Desktop     | [201ba6cbba](https://bsd-hardware.info/?probe=201ba6cbba) | Nov 04, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| ASUSTek       | N3150M-E                    | Desktop     | [289423796b](https://bsd-hardware.info/?probe=289423796b) | Jul 17, 2021 |
| ASUSTek       | N3150M-E                    | Desktop     | [64d08bd493](https://bsd-hardware.info/?probe=64d08bd493) | Jul 17, 2021 |
| PC Engines    | APU                         | Desktop     | [60d7917c9d](https://bsd-hardware.info/?probe=60d7917c9d) | Mar 28, 2021 |
| Dell          | 02YYK5 A00                  | Desktop     | [d4708d5f62](https://bsd-hardware.info/?probe=d4708d5f62) | Mar 07, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [dadf566436](https://bsd-hardware.info/?probe=dadf566436) | Jan 06, 2021 |
| HP            | 18E7                        | Desktop     | [8c4d8cbfc9](https://bsd-hardware.info/?probe=8c4d8cbfc9) | Dec 22, 2020 |
| HP            | 213D A01                    | Desktop     | [623a12f06b](https://bsd-hardware.info/?probe=623a12f06b) | Dec 20, 2020 |
| AWOW          | PC BOX                      | Mini pc     | [c966a1e1f6](https://bsd-hardware.info/?probe=c966a1e1f6) | Dec 17, 2020 |
| Supermicro    | X7SPA-HF                    | Desktop     | [84225d9f44](https://bsd-hardware.info/?probe=84225d9f44) | Dec 16, 2020 |
| Netgate       | SG-5100 1                   | Desktop     | [8336fb3a61](https://bsd-hardware.info/?probe=8336fb3a61) | Dec 16, 2020 |
| Unknown       | Unknown                     | Desktop     | [237f10ea9c](https://bsd-hardware.info/?probe=237f10ea9c) | Dec 16, 2020 |
| AWOW          | PC BOX                      | Mini pc     | [e975767e84](https://bsd-hardware.info/?probe=e975767e84) | Dec 16, 2020 |
| Dell          | 02YYK5 A00                  | Desktop     | [3fc7c8bb8d](https://bsd-hardware.info/?probe=3fc7c8bb8d) | Nov 01, 2020 |
| TYAN Compu... | Unknown                     | Desktop     | [5ba6da7c5f](https://bsd-hardware.info/?probe=5ba6da7c5f) | Oct 29, 2020 |
| Protectli     | FW2B Ver                    | Desktop     | [4fcfd19048](https://bsd-hardware.info/?probe=4fcfd19048) | Sep 21, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| ADI Engine... | RCC-VE                      | Desktop     | [91f0c6425b](https://bsd-hardware.info/?probe=91f0c6425b) | Jun 03, 2020 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [215cea62e1](https://bsd-hardware.info/?probe=215cea62e1) | Jun 02, 2020 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [b8e364a2c0](https://bsd-hardware.info/?probe=b8e364a2c0) | May 07, 2020 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 21        | 95.45%  |
| arm   | 1         | 4.55%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 22        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 22        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 22        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 86.36%  |
| en_US   | 2         | 9.09%   |
| pt_BR   | 1         | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 14        | 63.64%  |
| EFI  | 8         | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 14        | 63.64%  |
| Zfs  | 8         | 36.36%  |

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


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Protectli        | 2         | 9.09%   |
| Intel            | 2         | 9.09%   |
| Hewlett-Packard  | 2         | 9.09%   |
| Dell             | 2         | 9.09%   |
| AWOW             | 2         | 9.09%   |
| ASUSTek Computer | 2         | 9.09%   |
| Unknown          | 2         | 9.09%   |
| ZOTAC            | 1         | 4.55%   |
| TYAN Computer    | 1         | 4.55%   |
| Supermicro       | 1         | 4.55%   |
| PC Engines       | 1         | 4.55%   |
| Netgate          | 1         | 4.55%   |
| Lenovo           | 1         | 4.55%   |
| Itautec          | 1         | 4.55%   |
| ADI Engineering  | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 3         | 13.64%  |
| Intel Q3XXG4-P V1.0               | 2         | 9.09%   |
| AWOW PC BOX                       | 2         | 9.09%   |
| ZOTAC ZBOX-CI323NANO              | 1         | 4.55%   |
| Supermicro X7SPA-HF               | 1         | 4.55%   |
| Protectli FW4B                    | 1         | 4.55%   |
| Protectli FW2B                    | 1         | 4.55%   |
| PC Engines APU                    | 1         | 4.55%   |
| Netgate SG-5100                   | 1         | 4.55%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1         | 4.55%   |
| Itautec Infoway                   | 1         | 4.55%   |
| HP t620 PLUS Quad Core TC         | 1         | 4.55%   |
| HP ProDesk 600 G1 SFF             | 1         | 4.55%   |
| Dell OptiPlex 990                 | 1         | 4.55%   |
| Dell OptiPlex 7020                | 1         | 4.55%   |
| ASUS P5Q SE PLUS                  | 1         | 4.55%   |
| ASUS All Series                   | 1         | 4.55%   |
| ADI Engineering RCC-VE            | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 3         | 13.64%  |
| Intel Q3XXG4-P         | 2         | 9.09%   |
| Dell OptiPlex          | 2         | 9.09%   |
| AWOW PC                | 2         | 9.09%   |
| ZOTAC ZBOX-CI323NANO   | 1         | 4.55%   |
| Supermicro X7SPA-HF    | 1         | 4.55%   |
| Protectli FW4B         | 1         | 4.55%   |
| Protectli FW2B         | 1         | 4.55%   |
| PC Engines APU         | 1         | 4.55%   |
| Netgate SG-5100        | 1         | 4.55%   |
| Lenovo ThinkCentre     | 1         | 4.55%   |
| Itautec Infoway        | 1         | 4.55%   |
| HP t620                | 1         | 4.55%   |
| HP ProDesk             | 1         | 4.55%   |
| ASUS P5Q               | 1         | 4.55%   |
| ASUS All               | 1         | 4.55%   |
| ADI Engineering RCC-VE | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 4         | 18.18%  |
| 2016    | 3         | 13.64%  |
| 2014    | 3         | 13.64%  |
| 2020    | 2         | 9.09%   |
| 2017    | 2         | 9.09%   |
| 2009    | 2         | 9.09%   |
| 2019    | 1         | 4.55%   |
| 2015    | 1         | 4.55%   |
| 2012    | 1         | 4.55%   |
| 2010    | 1         | 4.55%   |
| 2006    | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 19        | 86.36%  |
| Mini pc | 3         | 13.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 20        | 90.91%  |
| Yes  | 2         | 9.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 40.91%  |
| 8.01-16.0  | 9         | 40.91%  |
| 2.01-3.0   | 2         | 9.09%   |
| 16.01-24.0 | 2         | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 16        | 72.73%  |
| 0.51-1.0 | 4         | 18.18%  |
| 4.01-8.0 | 1         | 4.55%   |
| 2.01-3.0 | 1         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 17        | 77.27%  |
| 2      | 3         | 13.64%  |
| 0      | 2         | 9.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 90.91%  |
| Yes       | 2         | 9.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 95.45%  |
| No        | 1         | 4.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 16        | 72.73%  |
| Yes       | 6         | 27.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 19        | 86.36%  |
| Yes       | 3         | 13.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 15        | 68.18%  |
| Taiwan      | 1         | 4.55%   |
| Sweden      | 1         | 4.55%   |
| Russia      | 1         | 4.55%   |
| Netherlands | 1         | 4.55%   |
| India       | 1         | 4.55%   |
| Greece      | 1         | 4.55%   |
| Brazil      | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Salem             | 2         | 9.09%   |
| Yegor'yevsk       | 1         | 4.55%   |
| Silver Spring     | 1         | 4.55%   |
| Phoenix           | 1         | 4.55%   |
| Philadelphia      | 1         | 4.55%   |
| Pasadena          | 1         | 4.55%   |
| Malmo             | 1         | 4.55%   |
| Longmont          | 1         | 4.55%   |
| Long Beach        | 1         | 4.55%   |
| Lawrenceville     | 1         | 4.55%   |
| JaraguГЎ do Sul | 1         | 4.55%   |
| Hoboken           | 1         | 4.55%   |
| Fletcher          | 1         | 4.55%   |
| Fair Oaks         | 1         | 4.55%   |
| Douliu            | 1         | 4.55%   |
| Centreville       | 1         | 4.55%   |
| Bengaluru         | 1         | 4.55%   |
| Atlanta           | 1         | 4.55%   |
| Athens            | 1         | 4.55%   |
| Ashburn           | 1         | 4.55%   |
| Amsterdam         | 1         | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 27.27%  |
| Seagate             | 2         | 2      | 9.09%   |
| Samsung Electronics | 2         | 2      | 9.09%   |
| Intel               | 2         | 2      | 9.09%   |
| FORESEE             | 2         | 2      | 9.09%   |
| Apacer              | 2         | 2      | 9.09%   |
| WDC                 | 1         | 2      | 4.55%   |
| SPCC                | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| Phison              | 1         | 1      | 4.55%   |
| Hoodisk             | 1         | 1      | 4.55%   |
| China               | 1         | 2      | 4.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SUV500MS120G 120GB       | 2         | 9.09%   |
| WDC WD10EFRX-68FYTN0 1TB          | 1         | 4.55%   |
| SPCC Solid State Disk 120GB       | 1         | 4.55%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 4.55%   |
| Seagate ST3160023A 160GB          | 1         | 4.55%   |
| SanDisk SDSSDA120G 120GB          | 1         | 4.55%   |
| Samsung SSD RBX Series 64GB M     | 1         | 4.55%   |
| Samsung SSD 860 EVO 250GB         | 1         | 4.55%   |
| Phison SATA SSD 240GB             | 1         | 4.55%   |
| Kingston SUV500MS240G 240GB       | 1         | 4.55%   |
| Kingston SUV500M8120G 120GB       | 1         | 4.55%   |
| Kingston SNS4151S316G 16GB        | 1         | 4.55%   |
| Kingston RBUSNS8180DS3128GH 128GB | 1         | 4.55%   |
| Intel SSDSA2CW080G3 80GB          | 1         | 4.55%   |
| Intel SSDMCEAC030B3 32GB          | 1         | 4.55%   |
| Hoodisk SSD 32GB                  | 1         | 4.55%   |
| FORESEE 64GB SSD                  | 1         | 4.55%   |
| FORESEE 128GB SSD                 | 1         | 4.55%   |
| China SATA SSD 256GB              | 1         | 4.55%   |
| Apacer 64GB SATA Flash Drive      | 1         | 4.55%   |
| Apacer 32GB SATA Flash Drive      | 1         | 4.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 2      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 31.58%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Intel               | 2         | 2      | 10.53%  |
| FORESEE             | 2         | 2      | 10.53%  |
| Apacer              | 2         | 2      | 10.53%  |
| SPCC                | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| Phison              | 1         | 1      | 5.26%   |
| Hoodisk             | 1         | 1      | 5.26%   |
| China               | 1         | 2      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 17        | 20     | 85%     |
| HDD  | 3         | 4      | 15%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 24     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 22     | 95%     |
| 0.51-1.0   | 1         | 2      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 8         | 36.36%  |
| 51-100     | 5         | 22.73%  |
| 21-50      | 4         | 18.18%  |
| 1-20       | 3         | 13.64%  |
| 251-500    | 1         | 4.55%   |
| 501-1000   | 1         | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 21        | 95.45%  |
| 21-50   | 1         | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Kingston SNS4151S316G 16GB   | 1         | 1      | 50%     |
| Apacer 32GB SATA Flash Drive | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 1         | 1      | 50%     |
| Apacer   | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 100%    |

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


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 18        | 22     | 90%     |
| Malfunc | 2         | 2      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 18        | 78.26%  |
| AMD                | 3         | 13.04%  |
| Silicon Image      | 1         | 4.35%   |
| JMicron Technology | 1         | 4.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 18.52%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 7.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 7.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 7.41%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 3.7%    |
| JMicron JMB368 IDE controller                                                    | 1         | 3.7%    |
| Intel SATA Controller [RAID mode]                                                | 1         | 3.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 3.7%    |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1         | 3.7%    |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1         | 3.7%    |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1         | 3.7%    |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1         | 3.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 3.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 3.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 3.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 3.7%    |
| AMD AMD-8111 IDE                                                                 | 1         | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 17        | 77.27%  |
| IDE  | 3         | 13.64%  |
| RAID | 2         | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 18        | 81.82%  |
| AMD    | 3         | 13.64%  |
| ARM    | 1         | 4.55%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2         | 9.09%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 2         | 9.09%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 9.09%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1         | 4.55%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 4.55%   |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1         | 4.55%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 1         | 4.55%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1         | 4.55%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 1         | 4.55%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 1         | 4.55%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1         | 4.55%   |
| Intel Celeron CPU 450 @ 2.20GHz          | 1         | 4.55%   |
| Intel Atom CPU D525 @ 1.80GHz            | 1         | 4.55%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 1         | 4.55%   |
| Intel Atom CPU C2758 @ 2.40GHz           | 1         | 4.55%   |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1         | 4.55%   |
| AMD Opteron Processor 252                | 1         | 4.55%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 1         | 4.55%   |
| AMD G-T40E Processor                     | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Celeron    | 8         | 36.36%  |
| Intel Core i5    | 4         | 18.18%  |
| Intel Atom       | 3         | 13.64%  |
| Intel Core i7    | 2         | 9.09%   |
| Intel Core 2 Duo | 1         | 4.55%   |
| ARM Cortex       | 1         | 4.55%   |
| AMD Opteron      | 1         | 4.55%   |
| AMD GX           | 1         | 4.55%   |
| AMD G            | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 12        | 54.55%  |
| 2       | 6         | 27.27%  |
| Unknown | 3         | 13.64%  |
| 1       | 1         | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 20        | 90.91%  |
| 2       | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 16        | 72.73%  |
| 2       | 3         | 13.64%  |
| Unknown | 3         | 13.64%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 6         | 27.27%  |
| Goldmont    | 3         | 13.64%  |
| Unknown     | 3         | 13.64%  |
| Haswell     | 2         | 9.09%   |
| Broadwell   | 2         | 9.09%   |
| SandyBridge | 1         | 4.55%   |
| Penryn      | 1         | 4.55%   |
| K8 Hammer   | 1         | 4.55%   |
| IvyBridge   | 1         | 4.55%   |
| Bonnell     | 1         | 4.55%   |
| Bobcat      | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 14        | 77.78%  |
| AMD                        | 3         | 16.67%  |
| Matrox Electronics Systems | 1         | 5.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 27.78%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 11.11%  |
| Intel HD Graphics 6000                                                                   | 2         | 11.11%  |
| Intel HD Graphics 500                                                                    | 2         | 11.11%  |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 5.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 5.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 5.56%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1         | 5.56%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1         | 5.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 14        | 63.64%  |
| Other      | 4         | 18.18%  |
| 1 x AMD    | 3         | 13.64%  |
| 1 x Matrox | 1         | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 18        | 81.82%  |
| Unknown | 4         | 18.18%  |

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

Zero info for selected period =(

Monitor Model
-------------

Monitor models

Zero info for selected period =(

Monitor Resolution
------------------

Monitor screen resolution

Zero info for selected period =(

Monitor Diagonal
----------------

Diagonal size in inches

Zero info for selected period =(

Monitor Width
-------------

Physical width

Zero info for selected period =(

Aspect Ratio
------------

Proportional relationship between the width and the height

Zero info for selected period =(

Monitor Area
------------

Area in inch²

Zero info for selected period =(

Pixel Density
-------------

Pixels per inch

Zero info for selected period =(

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 22        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 51.61%  |
| Realtek Semiconductor | 8         | 25.81%  |
| Qualcomm Atheros      | 3         | 9.68%   |
| Broadcom              | 2         | 6.45%   |
| NetXen Incorporated   | 1         | 3.23%   |
| MediaTek              | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8         | 21.05%  |
| Intel I211 Gigabit Network Connection                                         | 4         | 10.53%  |
| Intel Wireless 3165                                                           | 3         | 7.89%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 7.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 5.26%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 5.26%   |
| Intel 82580 Gigabit Network Connection                                        | 2         | 5.26%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 5.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 2.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 2.63%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1         | 2.63%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 2.63%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 2.63%   |
| Intel Ethernet Connection I354                                                | 1         | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1         | 2.63%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 2.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 2.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 2.63%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 2.63%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 2.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Qualcomm Atheros | 3         | 50%     |
| Intel            | 3         | 50%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 3         | 50%     |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 33.33%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 56.52%  |
| Realtek Semiconductor | 8         | 34.78%  |
| Broadcom              | 2         | 8.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8         | 26.67%  |
| Intel I211 Gigabit Network Connection                                         | 4         | 13.33%  |
| Intel I210 Gigabit Network Connection                                         | 3         | 10%     |
| Intel Ethernet Connection I217-LM                                             | 2         | 6.67%   |
| Intel 82580 Gigabit Network Connection                                        | 2         | 6.67%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 6.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 3.33%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 3.33%   |
| Intel Ethernet Connection I354                                                | 1         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1         | 3.33%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 3.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 3.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 3.33%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 3.33%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 21        | 72.41%  |
| WiFi     | 6         | 20.69%  |
| Modem    | 1         | 3.45%   |
| Unknown  | 1         | 3.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 21        | 100%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 3     | 6         | 27.27%  |
| 5     | 5         | 22.73%  |
| 2     | 4         | 18.18%  |
| 6     | 3         | 13.64%  |
| 4     | 2         | 9.09%   |
| 8     | 1         | 4.55%   |
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


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3         | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface | 3         | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 12        | 85.71%  |
| AMD    | 2         | 14.29%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 21.05%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 10.53%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 10.53%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 10.53%  |
| Intel Broadwell-U Audio Controller                                                                | 2         | 10.53%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 10.53%  |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 5.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 5.26%   |
| AMD FCH Azalia Controller                                                                         | 1         | 5.26%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 5.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 5         | 23.81%  |
| Crucial             | 5         | 23.81%  |
| Samsung Electronics | 4         | 19.05%  |
| Unknown (ABCD)      | 2         | 9.52%   |
| Transcend           | 2         | 9.52%   |
| SK Hynix            | 1         | 4.76%   |
| Micron Technology   | 1         | 4.76%   |
| Kingston            | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                         | 2         | 9.52%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 2         | 9.52%   |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s     | 2         | 9.52%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s          | 1         | 4.76%   |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s                | 1         | 4.76%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1         | 4.76%   |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s        | 1         | 4.76%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s            | 1         | 4.76%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1         | 4.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 4.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 1         | 4.76%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 1         | 4.76%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 4.76%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 1         | 4.76%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s        | 1         | 4.76%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB DIMM DDR3 1600MT/s        | 1         | 4.76%   |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s        | 1         | 4.76%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 13        | 68.42%  |
| SDRAM  | 2         | 10.53%  |
| LPDDR4 | 2         | 10.53%  |
| DDR4   | 1         | 5.26%   |
| DDR2   | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 15        | 78.95%  |
| SODIMM | 4         | 21.05%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 10        | 52.63%  |
| 16384 | 4         | 21.05%  |
| 2048  | 4         | 21.05%  |
| 8192  | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 9         | 47.37%  |
| 2400    | 3         | 15.79%  |
| 1333    | 3         | 15.79%  |
| 800     | 2         | 10.53%  |
| Unknown | 2         | 10.53%  |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 11        | 50%     |
| 1     | 7         | 31.82%  |
| 2     | 2         | 9.09%   |
| 5     | 1         | 4.55%   |
| 3     | 1         | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 9         | 52.94%  |
| Bluetooth                | 4         | 23.53%  |
| Card reader              | 2         | 11.76%  |
| Network                  | 1         | 5.88%   |
| Net/wireless             | 1         | 5.88%   |

