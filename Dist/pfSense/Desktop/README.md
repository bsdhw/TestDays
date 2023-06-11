pfSense - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for pfSense.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 34

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 0AA0h                       | [bed2f4cfd7](https://bsd-hardware.info/?probe=bed2f4cfd7) | May 16, 2023 |
| Advantech     | UNO-2271G_V2                | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| HP            | 805D                        | [4912ca5cd6](https://bsd-hardware.info/?probe=4912ca5cd6) | Jan 11, 2023 |
| HP            | 805D                        | [3da9c57f1f](https://bsd-hardware.info/?probe=3da9c57f1f) | Jan 11, 2023 |
| Unknown       | Unknown                     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| ASUSTek       | A88XM-E                     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| Techvision    | TVI7309X B0                 | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5b73e61a78](https://bsd-hardware.info/?probe=5b73e61a78) | Jul 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | [699fea1ac9](https://bsd-hardware.info/?probe=699fea1ac9) | Jul 02, 2022 |
| Gigabyte      | B85M-D3H                    | [92f62da399](https://bsd-hardware.info/?probe=92f62da399) | Jun 22, 2022 |
| PC Engines    | APU2                        | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [8bbeb73a52](https://bsd-hardware.info/?probe=8bbeb73a52) | Jan 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | [98ed242ae0](https://bsd-hardware.info/?probe=98ed242ae0) | Jan 01, 2022 |
| Dell          | 06D7TR A02                  | [201ba6cbba](https://bsd-hardware.info/?probe=201ba6cbba) | Nov 04, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| ASUSTek       | N3150M-E                    | [289423796b](https://bsd-hardware.info/?probe=289423796b) | Jul 17, 2021 |
| ASUSTek       | N3150M-E                    | [64d08bd493](https://bsd-hardware.info/?probe=64d08bd493) | Jul 17, 2021 |
| PC Engines    | APU                         | [60d7917c9d](https://bsd-hardware.info/?probe=60d7917c9d) | Mar 28, 2021 |
| Dell          | 02YYK5 A00                  | [d4708d5f62](https://bsd-hardware.info/?probe=d4708d5f62) | Mar 07, 2021 |
| Unknown       | YL-J3160L4                  | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| Protectli     | FW4B Ver                    | [dadf566436](https://bsd-hardware.info/?probe=dadf566436) | Jan 06, 2021 |
| HP            | 18E7                        | [8c4d8cbfc9](https://bsd-hardware.info/?probe=8c4d8cbfc9) | Dec 22, 2020 |
| HP            | 213D A01                    | [623a12f06b](https://bsd-hardware.info/?probe=623a12f06b) | Dec 20, 2020 |
| Supermicro    | X7SPA-HF                    | [84225d9f44](https://bsd-hardware.info/?probe=84225d9f44) | Dec 16, 2020 |
| Netgate       | SG-5100 1                   | [8336fb3a61](https://bsd-hardware.info/?probe=8336fb3a61) | Dec 16, 2020 |
| Unknown       | Unknown                     | [237f10ea9c](https://bsd-hardware.info/?probe=237f10ea9c) | Dec 16, 2020 |
| Dell          | 02YYK5 A00                  | [3fc7c8bb8d](https://bsd-hardware.info/?probe=3fc7c8bb8d) | Nov 01, 2020 |
| TYAN Compu... | Unknown                     | [5ba6da7c5f](https://bsd-hardware.info/?probe=5ba6da7c5f) | Oct 29, 2020 |
| Protectli     | FW2B Ver                    | [4fcfd19048](https://bsd-hardware.info/?probe=4fcfd19048) | Sep 21, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| ADI Engine... | RCC-VE                      | [91f0c6425b](https://bsd-hardware.info/?probe=91f0c6425b) | Jun 03, 2020 |
| ASUSTek       | P5Q SE PLUS                 | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| pfSense 2.4.5       | 10       | 34.48%  |
| pfSense 2.6.0       | 7        | 24.14%  |
| pfSense 2.5.0       | 4        | 13.79%  |
| pfSense 12.3-STABLE | 4        | 13.79%  |
| pfSense 2.4.4       | 2        | 6.9%    |
| pfSense 12.2-STABLE | 2        | 6.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| pfSense | 28       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 27       | 96.43%  |
| arm   | 1        | 3.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 28       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 28       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 28       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 89.29%  |
| en_US   | 2        | 7.14%   |
| pt_BR   | 1        | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 16       | 57.14%  |
| EFI  | 12       | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 15       | 53.57%  |
| Ufs  | 13       | 46.43%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 21       | 75%     |
| MBR  | 7        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 14.29%  |
| ASUSTek Computer    | 3        | 10.71%  |
| Unknown             | 3        | 10.71%  |
| Protectli           | 2        | 7.14%   |
| PC Engines          | 2        | 7.14%   |
| Lenovo              | 2        | 7.14%   |
| Intel               | 2        | 7.14%   |
| Dell                | 2        | 7.14%   |
| TYAN Computer       | 1        | 3.57%   |
| Techvision          | 1        | 3.57%   |
| Supermicro          | 1        | 3.57%   |
| Netgate             | 1        | 3.57%   |
| Itautec             | 1        | 3.57%   |
| Gigabyte Technology | 1        | 3.57%   |
| Advantech           | 1        | 3.57%   |
| ADI Engineering     | 1        | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 4        | 14.29%  |
| Intel Q3XXG4-P V1.0               | 2        | 7.14%   |
| Techvision TVI7309X               | 1        | 3.57%   |
| Supermicro X7SPA-HF               | 1        | 3.57%   |
| Protectli FW4B                    | 1        | 3.57%   |
| Protectli FW2B                    | 1        | 3.57%   |
| PC Engines APU2                   | 1        | 3.57%   |
| PC Engines APU                    | 1        | 3.57%   |
| Netgate SG-5100                   | 1        | 3.57%   |
| Lenovo ThinkCentre M92p 3209D9U   | 1        | 3.57%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1        | 3.57%   |
| Itautec Infoway                   | 1        | 3.57%   |
| HP xw4600 Workstation             | 1        | 3.57%   |
| HP t620 PLUS Quad Core TC         | 1        | 3.57%   |
| HP ProDesk 600 G2 SFF             | 1        | 3.57%   |
| HP ProDesk 600 G1 SFF             | 1        | 3.57%   |
| Gigabyte B85M-D3H                 | 1        | 3.57%   |
| Dell OptiPlex 990                 | 1        | 3.57%   |
| Dell OptiPlex 7020                | 1        | 3.57%   |
| ASUS P5Q SE PLUS                  | 1        | 3.57%   |
| ASUS All Series                   | 1        | 3.57%   |
| ASUS A88XM-E                      | 1        | 3.57%   |
| Advantech UNO-2271G_V2            | 1        | 3.57%   |
| ADI Engineering RCC-VE            | 1        | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 4        | 14.29%  |
| Lenovo ThinkCentre     | 2        | 7.14%   |
| Intel Q3XXG4-P         | 2        | 7.14%   |
| HP ProDesk             | 2        | 7.14%   |
| Dell OptiPlex          | 2        | 7.14%   |
| Techvision TVI7309X    | 1        | 3.57%   |
| Supermicro X7SPA-HF    | 1        | 3.57%   |
| Protectli FW4B         | 1        | 3.57%   |
| Protectli FW2B         | 1        | 3.57%   |
| PC Engines APU2        | 1        | 3.57%   |
| PC Engines APU         | 1        | 3.57%   |
| Netgate SG-5100        | 1        | 3.57%   |
| Itautec Infoway        | 1        | 3.57%   |
| HP xw4600              | 1        | 3.57%   |
| HP t620                | 1        | 3.57%   |
| Gigabyte B85M-D3H      | 1        | 3.57%   |
| ASUS P5Q               | 1        | 3.57%   |
| ASUS All               | 1        | 3.57%   |
| ASUS A88XM-E           | 1        | 3.57%   |
| Advantech UNO-2271G    | 1        | 3.57%   |
| ADI Engineering RCC-VE | 1        | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 5        | 17.86%  |
| 2015    | 4        | 14.29%  |
| 2016    | 3        | 10.71%  |
| 2022    | 2        | 7.14%   |
| 2017    | 2        | 7.14%   |
| 2014    | 2        | 7.14%   |
| 2012    | 2        | 7.14%   |
| 2009    | 2        | 7.14%   |
| 2021    | 1        | 3.57%   |
| 2019    | 1        | 3.57%   |
| 2013    | 1        | 3.57%   |
| 2010    | 1        | 3.57%   |
| 2006    | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 28       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 89.29%  |
| Yes  | 3        | 10.71%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 10       | 35.71%  |
| 8.01-16.0   | 10       | 35.71%  |
| 16.01-24.0  | 4        | 14.29%  |
| 2.01-3.0    | 2        | 7.14%   |
| 32.01-64.0  | 1        | 3.57%   |
| 64.01-256.0 | 1        | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 18       | 64.29%  |
| 0.51-1.0 | 5        | 17.86%  |
| 4.01-8.0 | 2        | 7.14%   |
| 2.01-3.0 | 2        | 7.14%   |
| 1.01-2.0 | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 79.31%  |
| 2      | 3        | 10.34%  |
| 0      | 3        | 10.34%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 82.14%  |
| Yes       | 5        | 17.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 96.43%  |
| No        | 1        | 3.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 82.14%  |
| Yes       | 5        | 17.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 96.43%  |
| Yes       | 1        | 3.57%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 15       | 53.57%  |
| Germany     | 2        | 7.14%   |
| UK          | 1        | 3.57%   |
| Taiwan      | 1        | 3.57%   |
| Sweden      | 1        | 3.57%   |
| Russia      | 1        | 3.57%   |
| New Zealand | 1        | 3.57%   |
| Netherlands | 1        | 3.57%   |
| India       | 1        | 3.57%   |
| Greece      | 1        | 3.57%   |
| Canada      | 1        | 3.57%   |
| Cameroon    | 1        | 3.57%   |
| Brazil      | 1        | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Salem             | 2        | 7.14%   |
| Yegor'yevsk       | 1        | 3.57%   |
| Wellington        | 1        | 3.57%   |
| Waconia           | 1        | 3.57%   |
| Uxbridge          | 1        | 3.57%   |
| Stuttgart         | 1        | 3.57%   |
| Silver Spring     | 1        | 3.57%   |
| Renton            | 1        | 3.57%   |
| Pasadena          | 1        | 3.57%   |
| Malmo             | 1        | 3.57%   |
| Longmont          | 1        | 3.57%   |
| Long Beach        | 1        | 3.57%   |
| London            | 1        | 3.57%   |
| Lawrenceville     | 1        | 3.57%   |
| Kottenheim        | 1        | 3.57%   |
| JaraguГЎ do Sul | 1        | 3.57%   |
| Hoboken           | 1        | 3.57%   |
| Fletcher          | 1        | 3.57%   |
| Douliu            | 1        | 3.57%   |
| Douala            | 1        | 3.57%   |
| Daly City         | 1        | 3.57%   |
| Centreville       | 1        | 3.57%   |
| Bengaluru         | 1        | 3.57%   |
| Atlanta           | 1        | 3.57%   |
| Athens            | 1        | 3.57%   |
| Ashburn           | 1        | 3.57%   |
| Amsterdam         | 1        | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 6      | 21.43%  |
| Seagate             | 4        | 4      | 14.29%  |
| Samsung Electronics | 4        | 4      | 14.29%  |
| WDC                 | 2        | 3      | 7.14%   |
| Phison              | 2        | 2      | 7.14%   |
| Intel               | 2        | 2      | 7.14%   |
| Apacer              | 2        | 2      | 7.14%   |
| SPCC                | 1        | 1      | 3.57%   |
| SanDisk             | 1        | 1      | 3.57%   |
| Hoodisk             | 1        | 1      | 3.57%   |
| FORESEE             | 1        | 1      | 3.57%   |
| Crucial             | 1        | 1      | 3.57%   |
| China               | 1        | 2      | 3.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SUV500MS120G 120GB     | 2        | 7.14%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1        | 3.57%   |
| WDC WD10EFRX-68FYTN0 1TB        | 1        | 3.57%   |
| SPCC Solid State Disk 120GB     | 1        | 3.57%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 3.57%   |
| Seagate ST380815AS 80GB         | 1        | 3.57%   |
| Seagate ST3160023A 160GB        | 1        | 3.57%   |
| Seagate ST240HM000-1G5152 240GB | 1        | 3.57%   |
| SanDisk SDSSDP064G 64GB         | 1        | 3.57%   |
| Samsung SSD RBX Series 64GB M   | 1        | 3.57%   |
| Samsung SSD 860 EVO 250GB       | 1        | 3.57%   |
| Samsung SSD 850 EVO mSATA 250GB | 1        | 3.57%   |
| Samsung SSD 850 EVO 120GB       | 1        | 3.57%   |
| Phison SATA SSD 32GB            | 1        | 3.57%   |
| Phison SATA SSD 240GB           | 1        | 3.57%   |
| Kingston SUV500MS240G 240GB     | 1        | 3.57%   |
| Kingston SUV500M8120G 120GB     | 1        | 3.57%   |
| Kingston SNVS1000G 1TB          | 1        | 3.57%   |
| Kingston SNS4151S316G 16GB      | 1        | 3.57%   |
| Intel SSDSA2CW080G3 80GB        | 1        | 3.57%   |
| Intel SSDMCEAC030B3 32GB        | 1        | 3.57%   |
| Hoodisk SSD 32GB                | 1        | 3.57%   |
| FORESEE 64GB SSD                | 1        | 3.57%   |
| Crucial CT500P2SSD8 500GB       | 1        | 3.57%   |
| China SATA SSD 256GB            | 1        | 3.57%   |
| Apacer 64GB SATA Flash Drive    | 1        | 3.57%   |
| Apacer 32GB SATA Flash Drive    | 1        | 3.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 60%     |
| WDC     | 2        | 3      | 40%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 5      | 23.81%  |
| Samsung Electronics | 4        | 4      | 19.05%  |
| Phison              | 2        | 2      | 9.52%   |
| Intel               | 2        | 2      | 9.52%   |
| Apacer              | 2        | 2      | 9.52%   |
| SPCC                | 1        | 1      | 4.76%   |
| Seagate             | 1        | 1      | 4.76%   |
| SanDisk             | 1        | 1      | 4.76%   |
| Hoodisk             | 1        | 1      | 4.76%   |
| FORESEE             | 1        | 1      | 4.76%   |
| China               | 1        | 2      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 18       | 22     | 72%     |
| HDD  | 5        | 6      | 20%     |
| NVMe | 2        | 2      | 8%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 23       | 28     | 92%     |
| NVMe | 2        | 2      | 8%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 26     | 95.65%  |
| 0.51-1.0   | 1        | 2      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 51-100     | 8        | 28.57%  |
| 21-50      | 6        | 21.43%  |
| 101-250    | 6        | 21.43%  |
| 251-500    | 3        | 10.71%  |
| 1-20       | 3        | 10.71%  |
| 501-1000   | 2        | 7.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 27       | 96.43%  |
| 21-50   | 1        | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Kingston SNS4151S316G 16GB   | 1        | 1      | 50%     |
| Apacer 32GB SATA Flash Drive | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Kingston | 1        | 1      | 50%     |
| Apacer   | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 2        | 2      | 100%    |

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
| Works   | 23       | 28     | 92%     |
| Malfunc | 2        | 2      | 8%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 21       | 70%     |
| AMD                         | 5        | 16.67%  |
| Silicon Image               | 1        | 3.33%   |
| Micron/Crucial Technology   | 1        | 3.33%   |
| Kingston Technology Company | 1        | 3.33%   |
| JMicron Technology          | 1        | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 11.76%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3        | 8.82%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3        | 8.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2        | 5.88%   |
| Intel SATA Controller [RAID mode]                                                | 2        | 5.88%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1        | 2.94%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 2.94%   |
| Kingston Company NVMe Controller                                                 | 1        | 2.94%   |
| JMicron JMB368 IDE controller                                                    | 1        | 2.94%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1        | 2.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1        | 2.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 2.94%   |
| Intel Elkhart Lake SATA AHCI                                                     | 1        | 2.94%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1        | 2.94%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 2.94%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1        | 2.94%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1        | 2.94%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 2.94%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 2.94%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 2.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1        | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1        | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1        | 2.94%   |
| AMD AMD-8111 IDE                                                                 | 1        | 2.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 21       | 72.41%  |
| RAID | 3        | 10.34%  |
| IDE  | 3        | 10.34%  |
| NVMe | 2        | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 78.57%  |
| AMD    | 5        | 17.86%  |
| ARM    | 1        | 3.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2        | 7.14%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2        | 7.14%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 1        | 3.57%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1        | 3.57%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 3.57%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1        | 3.57%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 1        | 3.57%   |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1        | 3.57%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 1        | 3.57%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz    | 1        | 3.57%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1        | 3.57%   |
| Intel Celeron N6210 @ 1.20GHz            | 1        | 3.57%   |
| Intel Celeron N5105 @ 2.00GHz            | 1        | 3.57%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 1        | 3.57%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1        | 3.57%   |
| Intel Celeron CPU 450 @ 2.20GHz          | 1        | 3.57%   |
| Intel Atom CPU D525 @ 1.80GHz            | 1        | 3.57%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 1        | 3.57%   |
| Intel Atom CPU C2758 @ 2.40GHz           | 1        | 3.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1        | 3.57%   |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1        | 3.57%   |
| AMD Opteron Processor 252                | 1        | 3.57%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 1        | 3.57%   |
| AMD GX-412TC SOC                         | 1        | 3.57%   |
| AMD G-T40E Processor                     | 1        | 3.57%   |
| AMD Athlon X4 860K Quad Core Processor   | 1        | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 7        | 25%     |
| Intel Celeron     | 7        | 25%     |
| Intel Atom        | 3        | 10.71%  |
| Intel Core i7     | 2        | 7.14%   |
| AMD GX            | 2        | 7.14%   |
| Other             | 1        | 3.57%   |
| Intel Core 2 Quad | 1        | 3.57%   |
| Intel Core 2 Duo  | 1        | 3.57%   |
| ARM Cortex        | 1        | 3.57%   |
| AMD Opteron       | 1        | 3.57%   |
| AMD G             | 1        | 3.57%   |
| AMD Athlon X4     | 1        | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 17       | 60.71%  |
| 2       | 7        | 25%     |
| Unknown | 3        | 10.71%  |
| 1       | 1        | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 26       | 92.86%  |
| 2       | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 21       | 75%     |
| 2       | 4        | 14.29%  |
| Unknown | 3        | 10.71%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Silvermont  | 5        | 17.86%  |
| Unknown     | 5        | 17.86%  |
| Haswell     | 3        | 10.71%  |
| Penryn      | 2        | 7.14%   |
| IvyBridge   | 2        | 7.14%   |
| Broadwell   | 2        | 7.14%   |
| TigerLake   | 1        | 3.57%   |
| Steamroller | 1        | 3.57%   |
| Skylake     | 1        | 3.57%   |
| SandyBridge | 1        | 3.57%   |
| Puma        | 1        | 3.57%   |
| K8 Hammer   | 1        | 3.57%   |
| Goldmont    | 1        | 3.57%   |
| Bonnell     | 1        | 3.57%   |
| Bobcat      | 1        | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 17       | 77.27%  |
| AMD                        | 4        | 18.18%  |
| Matrox Electronics Systems | 1        | 4.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 18.18%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 13.64%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 9.09%   |
| Intel HD Graphics 6000                                                                   | 2        | 9.09%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 4.55%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 4.55%   |
| Intel HD Graphics 530                                                                    | 1        | 4.55%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 1        | 4.55%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 4.55%   |
| AMD RV710 [Radeon HD 4550]                                                               | 1        | 4.55%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1        | 4.55%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1        | 4.55%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 17       | 60.71%  |
| Other      | 6        | 21.43%  |
| 1 x AMD    | 4        | 14.29%  |
| 1 x Matrox | 1        | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 22       | 78.57%  |
| Unknown | 6        | 21.43%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 100%    |

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

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 28       | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 20       | 54.05%  |
| Realtek Semiconductor     | 8        | 21.62%  |
| Qualcomm Atheros          | 3        | 8.11%   |
| Broadcom                  | 3        | 8.11%   |
| Solarflare Communications | 1        | 2.7%    |
| NetXen Incorporated       | 1        | 2.7%    |
| MediaTek                  | 1        | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7        | 14.89%  |
| Intel I211 Gigabit Network Connection                                         | 5        | 10.64%  |
| Intel I210 Gigabit Network Connection                                         | 4        | 8.51%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 6.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2        | 4.26%   |
| Intel Ethernet Controller I225-V                                              | 2        | 4.26%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.26%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 4.26%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 2.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 2.13%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 2.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1        | 2.13%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1        | 2.13%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 2.13%   |
| Intel Wireless-AC 9260                                                        | 1        | 2.13%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 2.13%   |
| Intel Ethernet Connection I354                                                | 1        | 2.13%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.13%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.13%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 2.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 2.13%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 2.13%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 2.13%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Qualcomm Atheros      | 3        | 60%     |
| Realtek Semiconductor | 1        | 20%     |
| Intel                 | 1        | 20%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2        | 40%     |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1        | 20%     |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 20%     |
| Intel Wireless-AC 9260                                                  | 1        | 20%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 20       | 60.61%  |
| Realtek Semiconductor     | 8        | 24.24%  |
| Broadcom                  | 3        | 9.09%   |
| Solarflare Communications | 1        | 3.03%   |
| MediaTek                  | 1        | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7        | 17.07%  |
| Intel I211 Gigabit Network Connection                                         | 5        | 12.2%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 9.76%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 7.32%   |
| Intel Ethernet Controller I225-V                                              | 2        | 4.88%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.88%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 4.88%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 2.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 2.44%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 2.44%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 2.44%   |
| Intel Ethernet Connection I354                                                | 1        | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.44%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.44%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 2.44%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.44%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 2.44%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 2.44%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 2.44%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 81.82%  |
| WiFi     | 5        | 15.15%  |
| Unknown  | 1        | 3.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 5     | 7        | 25%     |
| 3     | 7        | 25%     |
| 2     | 5        | 17.86%  |
| 6     | 4        | 14.29%  |
| 4     | 3        | 10.71%  |
| 8     | 1        | 3.57%   |
| 0     | 1        | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 85.71%  |
| Yes  | 4        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Wireless-AC 9260 Bluetooth Adapter | 1        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 84.21%  |
| AMD    | 3        | 15.79%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 12.5%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 12.5%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 8.33%   |
| Intel Broadwell-U Audio Controller                                                                | 2        | 8.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 8.33%   |
| AMD FCH Azalia Controller                                                                         | 2        | 8.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1        | 4.17%   |
| Intel Jasper Lake HD Audio                                                                        | 1        | 4.17%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 1        | 4.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 4.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 4.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 4.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 4.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 25%     |
| Samsung Electronics | 5        | 17.86%  |
| Crucial             | 5        | 17.86%  |
| Transcend           | 2        | 7.14%   |
| SK hynix            | 2        | 7.14%   |
| V-Color             | 1        | 3.57%   |
| Unknown (0x1636)    | 1        | 3.57%   |
| Ramaxel Technology  | 1        | 3.57%   |
| Nanya Technology    | 1        | 3.57%   |
| Micron Technology   | 1        | 3.57%   |
| Kingston            | 1        | 3.57%   |
| Corsair             | 1        | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2        | 7.14%   |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s | 2        | 7.14%   |
| V-Color RAM TN432G32D822 32GB SODIMM DDR4 3200MT/s       | 1        | 3.57%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s      | 1        | 3.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1        | 3.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 3.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s            | 1        | 3.57%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 3.57%   |
| Unknown (0x1636) RAM 5.6.5 4GB SODIMM DDR4 2667MT/s      | 1        | 3.57%   |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s    | 1        | 3.57%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s        | 1        | 3.57%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 3.57%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 3.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 3.57%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 3.57%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 3.57%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 3.57%   |
| Ramaxel RAM RML1320KE48D8F-800 2GB DIMM DDR2 800MT/s     | 1        | 3.57%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s       | 1        | 3.57%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 3.57%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 3.57%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s   | 1        | 3.57%   |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s    | 1        | 3.57%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s    | 1        | 3.57%   |
| Corsair RAM CM2X1024-6400 1GB DIMM DDR2 800MT/s          | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 15       | 60%     |
| DDR4  | 5        | 20%     |
| SDRAM | 3        | 12%     |
| DDR2  | 2        | 8%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 66.67%  |
| SODIMM | 8        | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 14       | 56%     |
| 2048  | 5        | 20%     |
| 16384 | 2        | 8%      |
| 8192  | 2        | 8%      |
| 32768 | 1        | 4%      |
| 1024  | 1        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 41.67%  |
| 1333    | 4        | 16.67%  |
| 800     | 3        | 12.5%   |
| 3200    | 2        | 8.33%   |
| Unknown | 2        | 8.33%   |
| 2667    | 1        | 4.17%   |
| 2400    | 1        | 4.17%   |
| 2133    | 1        | 4.17%   |

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
| 1     | 13       | 46.43%  |
| 0     | 13       | 46.43%  |
| 3     | 1        | 3.57%   |
| 2     | 1        | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 13       | 76.47%  |
| Net/wireless             | 2        | 11.76%  |
| Network                  | 1        | 5.88%   |
| Bluetooth                | 1        | 5.88%   |

