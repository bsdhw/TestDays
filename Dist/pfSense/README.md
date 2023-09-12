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

Total: 40

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Techvision    | TVI7309X B0                 | Desktop     | [b6e5a7e7bc](https://bsd-hardware.info/?probe=b6e5a7e7bc) | Jun 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2d50927445](https://bsd-hardware.info/?probe=2d50927445) | Jun 18, 2023 |
| HP            | 0AA0h                       | Desktop     | [bed2f4cfd7](https://bsd-hardware.info/?probe=bed2f4cfd7) | May 16, 2023 |
| Advantech     | UNO-2271G_V2                | Desktop     | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
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
| pfSense 2.4.5       | 13        | 39.39%  |
| pfSense 2.6.0       | 7         | 21.21%  |
| pfSense 2.5.0       | 4         | 12.12%  |
| pfSense 12.3-STABLE | 4         | 12.12%  |
| pfSense 2.4.4       | 2         | 6.06%   |
| pfSense 12.2-STABLE | 2         | 6.06%   |
| pfSense 2.7.0       | 1         | 3.03%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| pfSense | 32        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 31        | 96.88%  |
| arm   | 1         | 3.13%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 32        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 32        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 32        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 87.5%   |
| en_US   | 2         | 6.25%   |
| pt_BR   | 1         | 3.13%   |
| C       | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 18        | 56.25%  |
| EFI  | 14        | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 16        | 50%     |
| Ufs  | 16        | 50%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 24        | 75%     |
| MBR  | 8         | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 12.5%   |
| ASUSTek Computer    | 3         | 9.38%   |
| Unknown             | 3         | 9.38%   |
| Techvision          | 2         | 6.25%   |
| Protectli           | 2         | 6.25%   |
| PC Engines          | 2         | 6.25%   |
| Lenovo              | 2         | 6.25%   |
| Intel               | 2         | 6.25%   |
| Dell                | 2         | 6.25%   |
| AWOW                | 2         | 6.25%   |
| ZOTAC               | 1         | 3.13%   |
| TYAN Computer       | 1         | 3.13%   |
| Supermicro          | 1         | 3.13%   |
| Netgate             | 1         | 3.13%   |
| Itautec             | 1         | 3.13%   |
| Gigabyte Technology | 1         | 3.13%   |
| Advantech           | 1         | 3.13%   |
| ADI Engineering     | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 4         | 12.5%   |
| Techvision TVI7309X               | 2         | 6.25%   |
| Intel Q3XXG4-P V1.0               | 2         | 6.25%   |
| AWOW PC BOX                       | 2         | 6.25%   |
| ZOTAC ZBOX-CI323NANO              | 1         | 3.13%   |
| Supermicro X7SPA-HF               | 1         | 3.13%   |
| Protectli FW4B                    | 1         | 3.13%   |
| Protectli FW2B                    | 1         | 3.13%   |
| PC Engines APU2                   | 1         | 3.13%   |
| PC Engines APU                    | 1         | 3.13%   |
| Netgate SG-5100                   | 1         | 3.13%   |
| Lenovo ThinkCentre M92p 3209D9U   | 1         | 3.13%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1         | 3.13%   |
| Itautec Infoway                   | 1         | 3.13%   |
| HP xw4600 Workstation             | 1         | 3.13%   |
| HP t620 PLUS Quad Core TC         | 1         | 3.13%   |
| HP ProDesk 600 G2 SFF             | 1         | 3.13%   |
| HP ProDesk 600 G1 SFF             | 1         | 3.13%   |
| Gigabyte B85M-D3H                 | 1         | 3.13%   |
| Dell OptiPlex 990                 | 1         | 3.13%   |
| Dell OptiPlex 7020                | 1         | 3.13%   |
| ASUS P5Q SE PLUS                  | 1         | 3.13%   |
| ASUS All Series                   | 1         | 3.13%   |
| ASUS A88XM-E                      | 1         | 3.13%   |
| Advantech UNO-2271G_V2            | 1         | 3.13%   |
| ADI Engineering RCC-VE            | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 4         | 12.5%   |
| Techvision TVI7309X    | 2         | 6.25%   |
| Lenovo ThinkCentre     | 2         | 6.25%   |
| Intel Q3XXG4-P         | 2         | 6.25%   |
| HP ProDesk             | 2         | 6.25%   |
| Dell OptiPlex          | 2         | 6.25%   |
| AWOW PC                | 2         | 6.25%   |
| ZOTAC ZBOX-CI323NANO   | 1         | 3.13%   |
| Supermicro X7SPA-HF    | 1         | 3.13%   |
| Protectli FW4B         | 1         | 3.13%   |
| Protectli FW2B         | 1         | 3.13%   |
| PC Engines APU2        | 1         | 3.13%   |
| PC Engines APU         | 1         | 3.13%   |
| Netgate SG-5100        | 1         | 3.13%   |
| Itautec Infoway        | 1         | 3.13%   |
| HP xw4600              | 1         | 3.13%   |
| HP t620                | 1         | 3.13%   |
| Gigabyte B85M-D3H      | 1         | 3.13%   |
| ASUS P5Q               | 1         | 3.13%   |
| ASUS All               | 1         | 3.13%   |
| ASUS A88XM-E           | 1         | 3.13%   |
| Advantech UNO-2271G    | 1         | 3.13%   |
| ADI Engineering RCC-VE | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 5         | 15.63%  |
| 2016    | 4         | 12.5%   |
| 2015    | 4         | 12.5%   |
| 2022    | 3         | 9.38%   |
| 2020    | 2         | 6.25%   |
| 2017    | 2         | 6.25%   |
| 2014    | 2         | 6.25%   |
| 2012    | 2         | 6.25%   |
| 2009    | 2         | 6.25%   |
| 2021    | 1         | 3.13%   |
| 2019    | 1         | 3.13%   |
| 2013    | 1         | 3.13%   |
| 2010    | 1         | 3.13%   |
| 2006    | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 29        | 90.63%  |
| Mini pc | 3         | 9.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 90.63%  |
| Yes  | 3         | 9.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 40.63%  |
| 8.01-16.0   | 10        | 31.25%  |
| 16.01-24.0  | 5         | 15.63%  |
| 2.01-3.0    | 2         | 6.25%   |
| 32.01-64.0  | 1         | 3.13%   |
| 64.01-256.0 | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 21        | 65.63%  |
| 0.51-1.0 | 6         | 18.75%  |
| 4.01-8.0 | 2         | 6.25%   |
| 2.01-3.0 | 2         | 6.25%   |
| 1.01-2.0 | 1         | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 81.82%  |
| 2      | 3         | 9.09%   |
| 0      | 3         | 9.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 84.38%  |
| Yes       | 5         | 15.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 96.88%  |
| No        | 1         | 3.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 75%     |
| Yes       | 8         | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 87.5%   |
| Yes       | 4         | 12.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 18        | 56.25%  |
| Germany     | 2         | 6.25%   |
| Brazil      | 2         | 6.25%   |
| UK          | 1         | 3.13%   |
| Taiwan      | 1         | 3.13%   |
| Sweden      | 1         | 3.13%   |
| Russia      | 1         | 3.13%   |
| New Zealand | 1         | 3.13%   |
| Netherlands | 1         | 3.13%   |
| India       | 1         | 3.13%   |
| Greece      | 1         | 3.13%   |
| Canada      | 1         | 3.13%   |
| Cameroon    | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Salem             | 2         | 6.25%   |
| Yegor'yevsk       | 1         | 3.13%   |
| Wellington        | 1         | 3.13%   |
| Waconia           | 1         | 3.13%   |
| Uxbridge          | 1         | 3.13%   |
| Stuttgart         | 1         | 3.13%   |
| Silver Spring     | 1         | 3.13%   |
| Renton            | 1         | 3.13%   |
| Phoenix           | 1         | 3.13%   |
| Philadelphia      | 1         | 3.13%   |
| Pasadena          | 1         | 3.13%   |
| Malmo             | 1         | 3.13%   |
| Longmont          | 1         | 3.13%   |
| Long Beach        | 1         | 3.13%   |
| London            | 1         | 3.13%   |
| Lawrenceville     | 1         | 3.13%   |
| Kottenheim        | 1         | 3.13%   |
| JaraguГЎ do Sul | 1         | 3.13%   |
| Jaraguá do Sul   | 1         | 3.13%   |
| Hoboken           | 1         | 3.13%   |
| Fletcher          | 1         | 3.13%   |
| Fair Oaks         | 1         | 3.13%   |
| Douliu            | 1         | 3.13%   |
| Douala            | 1         | 3.13%   |
| Daly City         | 1         | 3.13%   |
| Centreville       | 1         | 3.13%   |
| Bengaluru         | 1         | 3.13%   |
| Atlanta           | 1         | 3.13%   |
| Athens            | 1         | 3.13%   |
| Ashburn           | 1         | 3.13%   |
| Amsterdam         | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 7      | 21.88%  |
| Seagate             | 4         | 4      | 12.5%   |
| Samsung Electronics | 4         | 4      | 12.5%   |
| WDC                 | 2         | 3      | 6.25%   |
| SanDisk             | 2         | 2      | 6.25%   |
| Phison              | 2         | 2      | 6.25%   |
| Intel               | 2         | 2      | 6.25%   |
| FORESEE             | 2         | 2      | 6.25%   |
| Apacer              | 2         | 2      | 6.25%   |
| SPCC                | 1         | 1      | 3.13%   |
| Silicon Motion      | 1         | 1      | 3.13%   |
| Hoodisk             | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |
| China               | 1         | 2      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SUV500MS120G 120GB       | 2         | 6.25%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 3.13%   |
| WDC WD10EFRX-68FYTN0 1TB          | 1         | 3.13%   |
| SPCC Solid State Disk 120GB       | 1         | 3.13%   |
| Silicon Motion NVME SSD 128GB     | 1         | 3.13%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 3.13%   |
| Seagate ST380815AS 80GB           | 1         | 3.13%   |
| Seagate ST3160023A 160GB          | 1         | 3.13%   |
| Seagate ST240HM000-1G5152 240GB   | 1         | 3.13%   |
| SanDisk SDSSDP064G 64GB           | 1         | 3.13%   |
| SanDisk SDSSDA120G 120GB          | 1         | 3.13%   |
| Samsung SSD RBX Series 64GB M     | 1         | 3.13%   |
| Samsung SSD 860 EVO 250GB         | 1         | 3.13%   |
| Samsung SSD 850 EVO mSATA 250GB   | 1         | 3.13%   |
| Samsung SSD 850 EVO 120GB         | 1         | 3.13%   |
| Phison SATA SSD 32GB              | 1         | 3.13%   |
| Phison SATA SSD 240GB             | 1         | 3.13%   |
| Kingston SUV500MS240G 240GB       | 1         | 3.13%   |
| Kingston SUV500M8120G 120GB       | 1         | 3.13%   |
| Kingston SNVS1000G 1TB            | 1         | 3.13%   |
| Kingston SNS4151S316G 16GB        | 1         | 3.13%   |
| Kingston RBUSNS8180DS3128GH 128GB | 1         | 3.13%   |
| Intel SSDSA2CW080G3 80GB          | 1         | 3.13%   |
| Intel SSDMCEAC030B3 32GB          | 1         | 3.13%   |
| Hoodisk SSD 32GB                  | 1         | 3.13%   |
| FORESEE 64GB SSD                  | 1         | 3.13%   |
| FORESEE 128GB SSD                 | 1         | 3.13%   |
| Crucial CT500P2SSD8 500GB         | 1         | 3.13%   |
| China SATA SSD 256GB              | 1         | 3.13%   |
| Apacer 64GB SATA Flash Drive      | 1         | 3.13%   |
| Apacer 32GB SATA Flash Drive      | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 60%     |
| WDC     | 2         | 3      | 40%     |

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
| SSD  | 21        | 25     | 72.41%  |
| HDD  | 5         | 6      | 17.24%  |
| NVMe | 3         | 3      | 10.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 31     | 89.66%  |
| NVMe | 3         | 3      | 10.34%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 29     | 96.15%  |
| 0.51-1.0   | 1         | 2      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 31.25%  |
| 51-100     | 8         | 25%     |
| 21-50      | 6         | 18.75%  |
| 251-500    | 3         | 9.38%   |
| 1-20       | 3         | 9.38%   |
| 501-1000   | 2         | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 31        | 96.88%  |
| 21-50   | 1         | 3.13%   |

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
| Works   | 27        | 32     | 93.1%   |
| Malfunc | 2         | 2      | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 24        | 70.59%  |
| AMD                         | 5         | 14.71%  |
| Silicon Motion              | 1         | 2.94%   |
| Silicon Image               | 1         | 2.94%   |
| Micron/Crucial Technology   | 1         | 2.94%   |
| Kingston Technology Company | 1         | 2.94%   |
| JMicron Technology          | 1         | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 13.16%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 7.89%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 7.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 5.26%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 5.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 5.26%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 2.63%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 2.63%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 2.63%   |
| Kingston Company NVMe Controller                                                 | 1         | 2.63%   |
| JMicron JMB368 IDE controller                                                    | 1         | 2.63%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.63%   |
| Intel Elkhart Lake SATA AHCI                                                     | 1         | 2.63%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1         | 2.63%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1         | 2.63%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1         | 2.63%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1         | 2.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 2.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 2.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.63%   |
| AMD AMD-8111 IDE                                                                 | 1         | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 72.73%  |
| RAID | 3         | 9.09%   |
| NVMe | 3         | 9.09%   |
| IDE  | 3         | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 81.25%  |
| AMD    | 5         | 15.63%  |
| ARM    | 1         | 3.13%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2         | 6.25%   |
| Intel Celeron N5105 @ 2.00GHz            | 2         | 6.25%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 2         | 6.25%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 6.25%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 1         | 3.13%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1         | 3.13%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 3.13%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1         | 3.13%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 1         | 3.13%   |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1         | 3.13%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 1         | 3.13%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz    | 1         | 3.13%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1         | 3.13%   |
| Intel Celeron N6210 @ 1.20GHz            | 1         | 3.13%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 1         | 3.13%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 1         | 3.13%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1         | 3.13%   |
| Intel Celeron CPU 450 @ 2.20GHz          | 1         | 3.13%   |
| Intel Atom CPU D525 @ 1.80GHz            | 1         | 3.13%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 1         | 3.13%   |
| Intel Atom CPU C2758 @ 2.40GHz           | 1         | 3.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1         | 3.13%   |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1         | 3.13%   |
| AMD Opteron Processor 252                | 1         | 3.13%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 1         | 3.13%   |
| AMD GX-412TC SOC                         | 1         | 3.13%   |
| AMD G-T40E Processor                     | 1         | 3.13%   |
| AMD Athlon X4 860K Quad Core Processor   | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Celeron     | 11        | 34.38%  |
| Intel Core i5     | 7         | 21.88%  |
| Intel Atom        | 3         | 9.38%   |
| Intel Core i7     | 2         | 6.25%   |
| AMD GX            | 2         | 6.25%   |
| Other             | 1         | 3.13%   |
| Intel Core 2 Quad | 1         | 3.13%   |
| Intel Core 2 Duo  | 1         | 3.13%   |
| ARM Cortex        | 1         | 3.13%   |
| AMD Opteron       | 1         | 3.13%   |
| AMD G             | 1         | 3.13%   |
| AMD Athlon X4     | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 21        | 65.63%  |
| 2       | 7         | 21.88%  |
| Unknown | 3         | 9.38%   |
| 1       | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 30        | 93.75%  |
| 2       | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 25        | 78.13%  |
| 2       | 4         | 12.5%   |
| Unknown | 3         | 9.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 6         | 18.75%  |
| Unknown     | 6         | 18.75%  |
| Haswell     | 3         | 9.38%   |
| Goldmont    | 3         | 9.38%   |
| Penryn      | 2         | 6.25%   |
| IvyBridge   | 2         | 6.25%   |
| Broadwell   | 2         | 6.25%   |
| TigerLake   | 1         | 3.13%   |
| Steamroller | 1         | 3.13%   |
| Skylake     | 1         | 3.13%   |
| SandyBridge | 1         | 3.13%   |
| Puma        | 1         | 3.13%   |
| K8 Hammer   | 1         | 3.13%   |
| Bonnell     | 1         | 3.13%   |
| Bobcat      | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 21        | 80.77%  |
| AMD                        | 4         | 15.38%  |
| Matrox Electronics Systems | 1         | 3.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 19.23%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 11.54%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 7.69%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 7.69%   |
| Intel HD Graphics 6000                                                                   | 2         | 7.69%   |
| Intel HD Graphics 500                                                                    | 2         | 7.69%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 3.85%   |
| Intel HD Graphics 530                                                                    | 1         | 3.85%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 1         | 3.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 3.85%   |
| AMD RV710 [Radeon HD 4550]                                                               | 1         | 3.85%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1         | 3.85%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1         | 3.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 21        | 65.63%  |
| Other      | 6         | 18.75%  |
| 1 x AMD    | 4         | 12.5%   |
| 1 x Matrox | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 26        | 81.25%  |
| Unknown | 6         | 18.75%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 100%    |

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
| 0     | 32        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 24        | 54.55%  |
| Realtek Semiconductor     | 11        | 25%     |
| Qualcomm Atheros          | 3         | 6.82%   |
| Broadcom                  | 3         | 6.82%   |
| Solarflare Communications | 1         | 2.27%   |
| NetXen Incorporated       | 1         | 2.27%   |
| MediaTek                  | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 10        | 18.52%  |
| Intel I211 Gigabit Network Connection                                         | 5         | 9.26%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 7.41%   |
| Intel Wireless 3165                                                           | 3         | 5.56%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 5.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 3.7%    |
| Intel Ethernet Controller I225-V                                              | 2         | 3.7%    |
| Intel Ethernet Connection I217-LM                                             | 2         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.7%    |
| Intel 82574L Gigabit Network Connection                                       | 2         | 3.7%    |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 1.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 1.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 1.85%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1         | 1.85%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 1.85%   |
| Intel Wireless-AC 9260                                                        | 1         | 1.85%   |
| Intel Ethernet Controller I226-V                                              | 1         | 1.85%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 1.85%   |
| Intel Ethernet Connection I354                                                | 1         | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 1.85%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 1.85%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 1.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 1.85%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.85%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 1.85%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 4         | 50%     |
| Qualcomm Atheros      | 3         | 37.5%   |
| Realtek Semiconductor | 1         | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 3         | 37.5%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 25%     |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 12.5%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 12.5%   |
| Intel Wireless-AC 9260                                                  | 1         | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 21        | 56.76%  |
| Realtek Semiconductor     | 11        | 29.73%  |
| Broadcom                  | 3         | 8.11%   |
| Solarflare Communications | 1         | 2.7%    |
| MediaTek                  | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 10        | 22.22%  |
| Intel I211 Gigabit Network Connection                                         | 5         | 11.11%  |
| Intel I210 Gigabit Network Connection                                         | 4         | 8.89%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 6.67%   |
| Intel Ethernet Controller I225-V                                              | 2         | 4.44%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 4.44%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 4.44%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 2.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 2.22%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 2.22%   |
| Intel Ethernet Controller I226-V                                              | 1         | 2.22%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 2.22%   |
| Intel Ethernet Connection I354                                                | 1         | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 2.22%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 2.22%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 2.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 2.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 2.22%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 2.22%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 2.22%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 77.5%   |
| WiFi     | 8         | 20%     |
| Unknown  | 1         | 2.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 100%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 3     | 10        | 31.25%  |
| 5     | 7         | 21.88%  |
| 2     | 5         | 15.63%  |
| 6     | 4         | 12.5%   |
| 4     | 4         | 12.5%   |
| 8     | 1         | 3.13%   |
| 0     | 1         | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 87.5%   |
| Yes  | 4         | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 4         | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface       | 3         | 75%     |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1         | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 86.96%  |
| AMD    | 3         | 13.04%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 14.29%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 10.71%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 7.14%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 7.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 7.14%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 7.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 7.14%   |
| AMD FCH Azalia Controller                                                                         | 2         | 7.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 3.57%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 1         | 3.57%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 3.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 3.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 3.57%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 3.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 21.88%  |
| Crucial             | 6         | 18.75%  |
| Samsung Electronics | 5         | 15.63%  |
| Unknown (ABCD)      | 2         | 6.25%   |
| Transcend           | 2         | 6.25%   |
| SK hynix            | 2         | 6.25%   |
| Micron Technology   | 2         | 6.25%   |
| V-Color             | 1         | 3.13%   |
| Unknown (0x1636)    | 1         | 3.13%   |
| Ramaxel Technology  | 1         | 3.13%   |
| Nanya Technology    | 1         | 3.13%   |
| Kingston            | 1         | 3.13%   |
| Corsair             | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                           | 2         | 6.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2         | 6.25%   |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s       | 2         | 6.25%   |
| V-Color RAM TN432G32D822 32GB SODIMM DDR4 3200MT/s             | 1         | 3.13%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 1         | 3.13%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1         | 3.13%   |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s                  | 1         | 3.13%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1         | 3.13%   |
| Unknown (0x1636) RAM 5.6.5 4GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s          | 1         | 3.13%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s              | 1         | 3.13%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s                     | 1         | 3.13%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1         | 3.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1         | 3.13%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s            | 1         | 3.13%   |
| Ramaxel RAM RML1320KE48D8F-800 2GB DIMM DDR2 800MT/s           | 1         | 3.13%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s             | 1         | 3.13%   |
| Micron RAM MTA8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 1         | 3.13%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s          | 1         | 3.13%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s         | 1         | 3.13%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB DIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s          | 1         | 3.13%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Corsair RAM CM2X1024-6400 1GB DIMM DDR2 800MT/s                | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 55.17%  |
| DDR4   | 6         | 20.69%  |
| SDRAM  | 3         | 10.34%  |
| LPDDR4 | 2         | 6.9%    |
| DDR2   | 2         | 6.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 19        | 67.86%  |
| SODIMM | 9         | 32.14%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 15        | 51.72%  |
| 2048  | 5         | 17.24%  |
| 16384 | 4         | 13.79%  |
| 8192  | 3         | 10.34%  |
| 32768 | 1         | 3.45%   |
| 1024  | 1         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 11        | 39.29%  |
| 1333    | 4         | 14.29%  |
| 3200    | 3         | 10.71%  |
| 2400    | 3         | 10.71%  |
| 800     | 3         | 10.71%  |
| Unknown | 2         | 7.14%   |
| 2667    | 1         | 3.57%   |
| 2133    | 1         | 3.57%   |

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
| 1     | 14        | 43.75%  |
| 0     | 13        | 40.63%  |
| 3     | 2         | 6.25%   |
| 2     | 2         | 6.25%   |
| 5     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 16        | 59.26%  |
| Bluetooth                | 5         | 18.52%  |
| Net/wireless             | 3         | 11.11%  |
| Card reader              | 2         | 7.41%   |
| Network                  | 1         | 3.7%    |

