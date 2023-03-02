pfSense - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for pfSense.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/pfSense/Desktop/README.md) and [notebooks](/Dist/pfSense/Notebook/README.md).

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

Total: 36

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | 805D                        | Desktop     | [4912ca5cd6](https://bsd-hardware.info/?probe=4912ca5cd6) | Jan 11, 2023 |
| HP            | 805D                        | Desktop     | [3da9c57f1f](https://bsd-hardware.info/?probe=3da9c57f1f) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5b73e61a78](https://bsd-hardware.info/?probe=5b73e61a78) | Jul 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [699fea1ac9](https://bsd-hardware.info/?probe=699fea1ac9) | Jul 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [92f62da399](https://bsd-hardware.info/?probe=92f62da399) | Jun 22, 2022 |
| PC Engines    | APU2                        | Desktop     | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
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

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| pfSense 2.4.5       | 13        | 43.33%  |
| pfSense 2.6.0       | 5         | 16.67%  |
| pfSense 2.5.0       | 4         | 13.33%  |
| pfSense 12.3-STABLE | 4         | 13.33%  |
| pfSense 2.4.4       | 2         | 6.67%   |
| pfSense 12.2-STABLE | 2         | 6.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| pfSense | 29        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 28        | 96.55%  |
| arm   | 1         | 3.45%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 29        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 29        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 29        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 89.66%  |
| en_US   | 2         | 6.9%    |
| pt_BR   | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 17        | 58.62%  |
| EFI  | 12        | 41.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 15        | 51.72%  |
| Zfs  | 14        | 48.28%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 21        | 72.41%  |
| MBR  | 8         | 27.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 10.34%  |
| ASUSTek Computer    | 3         | 10.34%  |
| Unknown             | 3         | 10.34%  |
| Protectli           | 2         | 6.9%    |
| PC Engines          | 2         | 6.9%    |
| Lenovo              | 2         | 6.9%    |
| Intel               | 2         | 6.9%    |
| Dell                | 2         | 6.9%    |
| AWOW                | 2         | 6.9%    |
| ZOTAC               | 1         | 3.45%   |
| TYAN Computer       | 1         | 3.45%   |
| Techvision          | 1         | 3.45%   |
| Supermicro          | 1         | 3.45%   |
| Netgate             | 1         | 3.45%   |
| Itautec             | 1         | 3.45%   |
| Gigabyte Technology | 1         | 3.45%   |
| ADI Engineering     | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 4         | 13.79%  |
| Intel Q3XXG4-P V1.0               | 2         | 6.9%    |
| AWOW PC BOX                       | 2         | 6.9%    |
| ZOTAC ZBOX-CI323NANO              | 1         | 3.45%   |
| Techvision TVI7309X               | 1         | 3.45%   |
| Supermicro X7SPA-HF               | 1         | 3.45%   |
| Protectli FW4B                    | 1         | 3.45%   |
| Protectli FW2B                    | 1         | 3.45%   |
| PC Engines APU2                   | 1         | 3.45%   |
| PC Engines APU                    | 1         | 3.45%   |
| Netgate SG-5100                   | 1         | 3.45%   |
| Lenovo ThinkCentre M92p 3209D9U   | 1         | 3.45%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1         | 3.45%   |
| Itautec Infoway                   | 1         | 3.45%   |
| HP t620 PLUS Quad Core TC         | 1         | 3.45%   |
| HP ProDesk 600 G2 SFF             | 1         | 3.45%   |
| HP ProDesk 600 G1 SFF             | 1         | 3.45%   |
| Gigabyte B85M-D3H                 | 1         | 3.45%   |
| Dell OptiPlex 990                 | 1         | 3.45%   |
| Dell OptiPlex 7020                | 1         | 3.45%   |
| ASUS P5Q SE PLUS                  | 1         | 3.45%   |
| ASUS All Series                   | 1         | 3.45%   |
| ASUS A88XM-E                      | 1         | 3.45%   |
| ADI Engineering RCC-VE            | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 4         | 13.79%  |
| Lenovo ThinkCentre     | 2         | 6.9%    |
| Intel Q3XXG4-P         | 2         | 6.9%    |
| HP ProDesk             | 2         | 6.9%    |
| Dell OptiPlex          | 2         | 6.9%    |
| AWOW PC                | 2         | 6.9%    |
| ZOTAC ZBOX-CI323NANO   | 1         | 3.45%   |
| Techvision TVI7309X    | 1         | 3.45%   |
| Supermicro X7SPA-HF    | 1         | 3.45%   |
| Protectli FW4B         | 1         | 3.45%   |
| Protectli FW2B         | 1         | 3.45%   |
| PC Engines APU2        | 1         | 3.45%   |
| PC Engines APU         | 1         | 3.45%   |
| Netgate SG-5100        | 1         | 3.45%   |
| Itautec Infoway        | 1         | 3.45%   |
| HP t620                | 1         | 3.45%   |
| Gigabyte B85M-D3H      | 1         | 3.45%   |
| ASUS P5Q               | 1         | 3.45%   |
| ASUS All               | 1         | 3.45%   |
| ASUS A88XM-E           | 1         | 3.45%   |
| ADI Engineering RCC-VE | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 5         | 17.24%  |
| 2016    | 4         | 13.79%  |
| 2015    | 4         | 13.79%  |
| 2020    | 2         | 6.9%    |
| 2017    | 2         | 6.9%    |
| 2014    | 2         | 6.9%    |
| 2009    | 2         | 6.9%    |
| 2022    | 1         | 3.45%   |
| 2021    | 1         | 3.45%   |
| 2019    | 1         | 3.45%   |
| 2013    | 1         | 3.45%   |
| 2012    | 1         | 3.45%   |
| 2010    | 1         | 3.45%   |
| 2006    | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 26        | 89.66%  |
| Mini pc | 3         | 10.34%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 89.66%  |
| Yes  | 3         | 10.34%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 37.93%  |
| 8.01-16.0   | 10        | 34.48%  |
| 16.01-24.0  | 4         | 13.79%  |
| 2.01-3.0    | 2         | 6.9%    |
| 32.01-64.0  | 1         | 3.45%   |
| 64.01-256.0 | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 19        | 65.52%  |
| 0.51-1.0 | 5         | 17.24%  |
| 4.01-8.0 | 2         | 6.9%    |
| 2.01-3.0 | 2         | 6.9%    |
| 1.01-2.0 | 1         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 83.33%  |
| 2      | 3         | 10%     |
| 0      | 2         | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 86.21%  |
| Yes       | 4         | 13.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 96.55%  |
| No        | 1         | 3.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 79.31%  |
| Yes       | 6         | 20.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 89.66%  |
| Yes       | 3         | 10.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 18        | 62.07%  |
| UK          | 1         | 3.45%   |
| Taiwan      | 1         | 3.45%   |
| Sweden      | 1         | 3.45%   |
| Russia      | 1         | 3.45%   |
| New Zealand | 1         | 3.45%   |
| Netherlands | 1         | 3.45%   |
| India       | 1         | 3.45%   |
| Greece      | 1         | 3.45%   |
| Germany     | 1         | 3.45%   |
| Canada      | 1         | 3.45%   |
| Brazil      | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Salem             | 2         | 6.9%    |
| Yegor'yevsk       | 1         | 3.45%   |
| Wellington        | 1         | 3.45%   |
| Waconia           | 1         | 3.45%   |
| Uxbridge          | 1         | 3.45%   |
| Silver Spring     | 1         | 3.45%   |
| Renton            | 1         | 3.45%   |
| Phoenix           | 1         | 3.45%   |
| Philadelphia      | 1         | 3.45%   |
| Pasadena          | 1         | 3.45%   |
| Malmo             | 1         | 3.45%   |
| Longmont          | 1         | 3.45%   |
| Long Beach        | 1         | 3.45%   |
| London            | 1         | 3.45%   |
| Lawrenceville     | 1         | 3.45%   |
| Kottenheim        | 1         | 3.45%   |
| JaraguГЎ do Sul | 1         | 3.45%   |
| Hoboken           | 1         | 3.45%   |
| Fletcher          | 1         | 3.45%   |
| Fair Oaks         | 1         | 3.45%   |
| Douliu            | 1         | 3.45%   |
| Daly City         | 1         | 3.45%   |
| Centreville       | 1         | 3.45%   |
| Bengaluru         | 1         | 3.45%   |
| Atlanta           | 1         | 3.45%   |
| Athens            | 1         | 3.45%   |
| Ashburn           | 1         | 3.45%   |
| Amsterdam         | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 23.33%  |
| Samsung Electronics | 4         | 4      | 13.33%  |
| Seagate             | 3         | 3      | 10%     |
| WDC                 | 2         | 3      | 6.67%   |
| SanDisk             | 2         | 2      | 6.67%   |
| Phison              | 2         | 2      | 6.67%   |
| Intel               | 2         | 2      | 6.67%   |
| FORESEE             | 2         | 2      | 6.67%   |
| Apacer              | 2         | 2      | 6.67%   |
| SPCC                | 1         | 1      | 3.33%   |
| Hoodisk             | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| China               | 1         | 2      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SUV500MS120G 120GB       | 2         | 6.67%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 3.33%   |
| WDC WD10EFRX-68FYTN0 1TB          | 1         | 3.33%   |
| SPCC Solid State Disk 120GB       | 1         | 3.33%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 3.33%   |
| Seagate ST3160023A 160GB          | 1         | 3.33%   |
| Seagate ST240HM000-1G5152 240GB   | 1         | 3.33%   |
| SanDisk SDSSDP064G 64GB           | 1         | 3.33%   |
| SanDisk SDSSDA120G 120GB          | 1         | 3.33%   |
| Samsung SSD RBX Series 64GB M     | 1         | 3.33%   |
| Samsung SSD 860 EVO 250GB         | 1         | 3.33%   |
| Samsung SSD 850 EVO mSATA 250GB   | 1         | 3.33%   |
| Samsung SSD 850 EVO 120GB         | 1         | 3.33%   |
| Phison SATA SSD 32GB              | 1         | 3.33%   |
| Phison SATA SSD 240GB             | 1         | 3.33%   |
| Kingston SUV500MS240G 240GB       | 1         | 3.33%   |
| Kingston SUV500M8120G 120GB       | 1         | 3.33%   |
| Kingston SNVS1000G 1TB            | 1         | 3.33%   |
| Kingston SNS4151S316G 16GB        | 1         | 3.33%   |
| Kingston RBUSNS8180DS3128GH 128GB | 1         | 3.33%   |
| Intel SSDSA2CW080G3 80GB          | 1         | 3.33%   |
| Intel SSDMCEAC030B3 32GB          | 1         | 3.33%   |
| Hoodisk SSD 32GB                  | 1         | 3.33%   |
| FORESEE 64GB SSD                  | 1         | 3.33%   |
| FORESEE 128GB SSD                 | 1         | 3.33%   |
| Crucial CT500P2SSD8 500GB         | 1         | 3.33%   |
| China SATA SSD 256GB              | 1         | 3.33%   |
| Apacer 64GB SATA Flash Drive      | 1         | 3.33%   |
| Apacer 32GB SATA Flash Drive      | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 3      | 50%     |
| Seagate | 2         | 2      | 50%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 25%     |
| Samsung Electronics | 4         | 4      | 16.67%  |
| SanDisk             | 2         | 2      | 8.33%   |
| Phison              | 2         | 2      | 8.33%   |
| Intel               | 2         | 2      | 8.33%   |
| FORESEE             | 2         | 2      | 8.33%   |
| Apacer              | 2         | 2      | 8.33%   |
| SPCC                | 1         | 1      | 4.17%   |
| Seagate             | 1         | 1      | 4.17%   |
| Hoodisk             | 1         | 1      | 4.17%   |
| China               | 1         | 2      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 21        | 25     | 77.78%  |
| HDD  | 4         | 5      | 14.81%  |
| NVMe | 2         | 2      | 7.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 30     | 92.59%  |
| NVMe | 2         | 2      | 7.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 28     | 96%     |
| 0.51-1.0   | 1         | 2      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 31.03%  |
| 51-100     | 7         | 24.14%  |
| 21-50      | 5         | 17.24%  |
| 251-500    | 3         | 10.34%  |
| 1-20       | 3         | 10.34%  |
| 501-1000   | 2         | 6.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 28        | 96.55%  |
| 21-50   | 1         | 3.45%   |

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
| Works   | 25        | 30     | 92.59%  |
| Malfunc | 2         | 2      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 22        | 70.97%  |
| AMD                         | 5         | 16.13%  |
| Silicon Image               | 1         | 3.23%   |
| Micron/Crucial Technology   | 1         | 3.23%   |
| Kingston Technology Company | 1         | 3.23%   |
| JMicron Technology          | 1         | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 14.29%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 8.57%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 8.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 5.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 5.71%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 2.86%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 2.86%   |
| JMicron JMB368 IDE controller                                                    | 1         | 2.86%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2.86%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.86%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1         | 2.86%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1         | 2.86%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1         | 2.86%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1         | 2.86%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 2.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 2.86%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.86%   |
| AMD AMD-8111 IDE                                                                 | 1         | 2.86%   |
| Unknown                                                                          | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 23        | 76.67%  |
| IDE  | 3         | 10%     |
| RAID | 2         | 6.67%   |
| NVMe | 2         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 79.31%  |
| AMD    | 5         | 17.24%  |
| ARM    | 1         | 3.45%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2         | 6.9%    |
| Intel Celeron CPU N3150 @ 1.60GHz        | 2         | 6.9%    |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 6.9%    |
| Intel Core i5-6500 CPU @ 3.20GHz         | 1         | 3.45%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1         | 3.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 3.45%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1         | 3.45%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 1         | 3.45%   |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1         | 3.45%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 1         | 3.45%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1         | 3.45%   |
| Intel Celeron N5105 @ 2.00GHz            | 1         | 3.45%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 1         | 3.45%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 1         | 3.45%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1         | 3.45%   |
| Intel Celeron CPU 450 @ 2.20GHz          | 1         | 3.45%   |
| Intel Atom CPU D525 @ 1.80GHz            | 1         | 3.45%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 1         | 3.45%   |
| Intel Atom CPU C2758 @ 2.40GHz           | 1         | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1         | 3.45%   |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1         | 3.45%   |
| AMD Opteron Processor 252                | 1         | 3.45%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 1         | 3.45%   |
| AMD GX-412TC SOC                         | 1         | 3.45%   |
| AMD G-T40E Processor                     | 1         | 3.45%   |
| AMD Athlon X4 860K Quad Core Processor   | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Celeron    | 9         | 31.03%  |
| Intel Core i5    | 7         | 24.14%  |
| Intel Atom       | 3         | 10.34%  |
| Intel Core i7    | 2         | 6.9%    |
| AMD GX           | 2         | 6.9%    |
| Other            | 1         | 3.45%   |
| Intel Core 2 Duo | 1         | 3.45%   |
| ARM Cortex       | 1         | 3.45%   |
| AMD Opteron      | 1         | 3.45%   |
| AMD G            | 1         | 3.45%   |
| AMD Athlon X4    | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 19        | 65.52%  |
| 2       | 6         | 20.69%  |
| Unknown | 3         | 10.34%  |
| 1       | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 27        | 93.1%   |
| 2       | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 22        | 75.86%  |
| 2       | 4         | 13.79%  |
| Unknown | 3         | 10.34%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 6         | 20.69%  |
| Unknown     | 4         | 13.79%  |
| Haswell     | 3         | 10.34%  |
| Goldmont    | 3         | 10.34%  |
| IvyBridge   | 2         | 6.9%    |
| Broadwell   | 2         | 6.9%    |
| TigerLake   | 1         | 3.45%   |
| Steamroller | 1         | 3.45%   |
| Skylake     | 1         | 3.45%   |
| SandyBridge | 1         | 3.45%   |
| Puma        | 1         | 3.45%   |
| Penryn      | 1         | 3.45%   |
| K8 Hammer   | 1         | 3.45%   |
| Bonnell     | 1         | 3.45%   |
| Bobcat      | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 19        | 82.61%  |
| AMD                        | 3         | 13.04%  |
| Matrox Electronics Systems | 1         | 4.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 21.74%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 13.04%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 8.7%    |
| Intel HD Graphics 6000                                                                   | 2         | 8.7%    |
| Intel HD Graphics 500                                                                    | 2         | 8.7%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 4.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 4.35%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 4.35%   |
| Intel HD Graphics 530                                                                    | 1         | 4.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 4.35%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1         | 4.35%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1         | 4.35%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 19        | 65.52%  |
| Other      | 6         | 20.69%  |
| 1 x AMD    | 3         | 10.34%  |
| 1 x Matrox | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 23        | 79.31%  |
| Unknown | 6         | 20.69%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 100%    |

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
| 0     | 29        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 22        | 55%     |
| Realtek Semiconductor     | 10        | 25%     |
| Qualcomm Atheros          | 3         | 7.5%    |
| Broadcom                  | 2         | 5%      |
| Solarflare Communications | 1         | 2.5%    |
| NetXen Incorporated       | 1         | 2.5%    |
| MediaTek                  | 1         | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 10        | 20.83%  |
| Intel I211 Gigabit Network Connection                                         | 4         | 8.33%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 8.33%   |
| Intel Wireless 3165                                                           | 3         | 6.25%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 6.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 4.17%   |
| Intel Ethernet Controller I225-V                                              | 2         | 4.17%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 4.17%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 4.17%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 2.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 2.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 2.08%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1         | 2.08%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 2.08%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 2.08%   |
| Intel Ethernet Connection I354                                                | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 2.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 2.08%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 2.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 2.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 2.08%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 2.08%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 2.08%   |

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


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 19        | 59.38%  |
| Realtek Semiconductor     | 10        | 31.25%  |
| Broadcom                  | 2         | 6.25%   |
| Solarflare Communications | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 10        | 25%     |
| Intel I211 Gigabit Network Connection                                         | 4         | 10%     |
| Intel I210 Gigabit Network Connection                                         | 4         | 10%     |
| Intel 82580 Gigabit Network Connection                                        | 3         | 7.5%    |
| Intel Ethernet Controller I225-V                                              | 2         | 5%      |
| Intel Ethernet Connection I217-LM                                             | 2         | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 5%      |
| Intel 82574L Gigabit Network Connection                                       | 2         | 5%      |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 2.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 2.5%    |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 2.5%    |
| Intel Ethernet Connection I354                                                | 1         | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 2.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 2.5%    |
| Intel 82576 Gigabit Network Connection                                        | 1         | 2.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 2.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 2.5%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 2.5%    |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 77.78%  |
| WiFi     | 6         | 16.67%  |
| Modem    | 1         | 2.78%   |
| Unknown  | 1         | 2.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 100%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 3     | 8         | 27.59%  |
| 5     | 7         | 24.14%  |
| 2     | 5         | 17.24%  |
| 6     | 4         | 13.79%  |
| 4     | 3         | 10.34%  |
| 8     | 1         | 3.45%   |
| 0     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25        | 86.21%  |
| Yes  | 4         | 13.79%  |

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
| Intel  | 17        | 85%     |
| AMD    | 3         | 15%     |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 16%     |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 12%     |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 8%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 8%      |
| Intel Broadwell-U Audio Controller                                                                | 2         | 8%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 8%      |
| AMD FCH Azalia Controller                                                                         | 2         | 8%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 4%      |
| Intel Jasper Lake HD Audio                                                                        | 1         | 4%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 4%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 4%      |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 4%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 25.93%  |
| Crucial             | 6         | 22.22%  |
| Samsung Electronics | 4         | 14.81%  |
| Unknown (ABCD)      | 2         | 7.41%   |
| Transcend           | 2         | 7.41%   |
| SK hynix            | 2         | 7.41%   |
| V-Color             | 1         | 3.7%    |
| Nanya Technology    | 1         | 3.7%    |
| Micron Technology   | 1         | 3.7%    |
| Kingston            | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                              | 2         | 7.41%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2         | 7.41%   |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s          | 2         | 7.41%   |
| V-Color RAM TN432G32D822 32GB SODIMM DDR4 3200MT/s                | 1         | 3.7%    |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s               | 1         | 3.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 1         | 3.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 1         | 3.7%    |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s                     | 1         | 3.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 1         | 3.7%    |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s             | 1         | 3.7%    |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s                 | 1         | 3.7%    |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s                        | 1         | 3.7%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 3.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 3.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 1         | 3.7%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s               | 1         | 3.7%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 1         | 3.7%    |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                | 1         | 3.7%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 1         | 3.7%    |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s             | 1         | 3.7%    |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s            | 1         | 3.7%    |
| Crucial RAM CT51264BF160BJ.M8F 4GB DIMM DDR3 1600MT/s             | 1         | 3.7%    |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s             | 1         | 3.7%    |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s             | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 64%     |
| DDR4   | 4         | 16%     |
| SDRAM  | 2         | 8%      |
| LPDDR4 | 2         | 8%      |
| DDR2   | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 18        | 72%     |
| SODIMM | 7         | 28%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 14        | 56%     |
| 16384 | 4         | 16%     |
| 2048  | 4         | 16%     |
| 8192  | 2         | 8%      |
| 32768 | 1         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 11        | 44%     |
| 1333    | 4         | 16%     |
| 2400    | 3         | 12%     |
| 3200    | 2         | 8%      |
| 800     | 2         | 8%      |
| Unknown | 2         | 8%      |
| 2133    | 1         | 4%      |

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
| 0     | 13        | 44.83%  |
| 1     | 12        | 41.38%  |
| 2     | 2         | 6.9%    |
| 5     | 1         | 3.45%   |
| 3     | 1         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 14        | 63.64%  |
| Bluetooth                | 4         | 18.18%  |
| Card reader              | 2         | 9.09%   |
| Network                  | 1         | 4.55%   |
| Net/wireless             | 1         | 4.55%   |

