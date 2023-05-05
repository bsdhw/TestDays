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

Total: 37

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| pfSense 2.4.5       | 13        | 41.94%  |
| pfSense 2.6.0       | 6         | 19.35%  |
| pfSense 2.5.0       | 4         | 12.9%   |
| pfSense 12.3-STABLE | 4         | 12.9%   |
| pfSense 2.4.4       | 2         | 6.45%   |
| pfSense 12.2-STABLE | 2         | 6.45%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| pfSense | 30        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 29        | 96.67%  |
| arm   | 1         | 3.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 30        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 30        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 30        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 90%     |
| en_US   | 2         | 6.67%   |
| pt_BR   | 1         | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 17        | 56.67%  |
| EFI  | 13        | 43.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 15        | 50%     |
| Ufs  | 15        | 50%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 22        | 73.33%  |
| MBR  | 8         | 26.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 10%     |
| ASUSTek Computer    | 3         | 10%     |
| Unknown             | 3         | 10%     |
| Protectli           | 2         | 6.67%   |
| PC Engines          | 2         | 6.67%   |
| Lenovo              | 2         | 6.67%   |
| Intel               | 2         | 6.67%   |
| Dell                | 2         | 6.67%   |
| AWOW                | 2         | 6.67%   |
| ZOTAC               | 1         | 3.33%   |
| TYAN Computer       | 1         | 3.33%   |
| Techvision          | 1         | 3.33%   |
| Supermicro          | 1         | 3.33%   |
| Netgate             | 1         | 3.33%   |
| Itautec             | 1         | 3.33%   |
| Gigabyte Technology | 1         | 3.33%   |
| Advantech           | 1         | 3.33%   |
| ADI Engineering     | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 4         | 13.33%  |
| Intel Q3XXG4-P V1.0               | 2         | 6.67%   |
| AWOW PC BOX                       | 2         | 6.67%   |
| ZOTAC ZBOX-CI323NANO              | 1         | 3.33%   |
| Techvision TVI7309X               | 1         | 3.33%   |
| Supermicro X7SPA-HF               | 1         | 3.33%   |
| Protectli FW4B                    | 1         | 3.33%   |
| Protectli FW2B                    | 1         | 3.33%   |
| PC Engines APU2                   | 1         | 3.33%   |
| PC Engines APU                    | 1         | 3.33%   |
| Netgate SG-5100                   | 1         | 3.33%   |
| Lenovo ThinkCentre M92p 3209D9U   | 1         | 3.33%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1         | 3.33%   |
| Itautec Infoway                   | 1         | 3.33%   |
| HP t620 PLUS Quad Core TC         | 1         | 3.33%   |
| HP ProDesk 600 G2 SFF             | 1         | 3.33%   |
| HP ProDesk 600 G1 SFF             | 1         | 3.33%   |
| Gigabyte B85M-D3H                 | 1         | 3.33%   |
| Dell OptiPlex 990                 | 1         | 3.33%   |
| Dell OptiPlex 7020                | 1         | 3.33%   |
| ASUS P5Q SE PLUS                  | 1         | 3.33%   |
| ASUS All Series                   | 1         | 3.33%   |
| ASUS A88XM-E                      | 1         | 3.33%   |
| Advantech UNO-2271G_V2            | 1         | 3.33%   |
| ADI Engineering RCC-VE            | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 4         | 13.33%  |
| Lenovo ThinkCentre     | 2         | 6.67%   |
| Intel Q3XXG4-P         | 2         | 6.67%   |
| HP ProDesk             | 2         | 6.67%   |
| Dell OptiPlex          | 2         | 6.67%   |
| AWOW PC                | 2         | 6.67%   |
| ZOTAC ZBOX-CI323NANO   | 1         | 3.33%   |
| Techvision TVI7309X    | 1         | 3.33%   |
| Supermicro X7SPA-HF    | 1         | 3.33%   |
| Protectli FW4B         | 1         | 3.33%   |
| Protectli FW2B         | 1         | 3.33%   |
| PC Engines APU2        | 1         | 3.33%   |
| PC Engines APU         | 1         | 3.33%   |
| Netgate SG-5100        | 1         | 3.33%   |
| Itautec Infoway        | 1         | 3.33%   |
| HP t620                | 1         | 3.33%   |
| Gigabyte B85M-D3H      | 1         | 3.33%   |
| ASUS P5Q               | 1         | 3.33%   |
| ASUS All               | 1         | 3.33%   |
| ASUS A88XM-E           | 1         | 3.33%   |
| Advantech UNO-2271G    | 1         | 3.33%   |
| ADI Engineering RCC-VE | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 5         | 16.67%  |
| 2016    | 4         | 13.33%  |
| 2015    | 4         | 13.33%  |
| 2022    | 2         | 6.67%   |
| 2020    | 2         | 6.67%   |
| 2017    | 2         | 6.67%   |
| 2014    | 2         | 6.67%   |
| 2009    | 2         | 6.67%   |
| 2021    | 1         | 3.33%   |
| 2019    | 1         | 3.33%   |
| 2013    | 1         | 3.33%   |
| 2012    | 1         | 3.33%   |
| 2010    | 1         | 3.33%   |
| 2006    | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 27        | 90%     |
| Mini pc | 3         | 10%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 90%     |
| Yes  | 3         | 10%     |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 12        | 40%     |
| 8.01-16.0   | 10        | 33.33%  |
| 16.01-24.0  | 4         | 13.33%  |
| 2.01-3.0    | 2         | 6.67%   |
| 32.01-64.0  | 1         | 3.33%   |
| 64.01-256.0 | 1         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 20        | 66.67%  |
| 0.51-1.0 | 5         | 16.67%  |
| 4.01-8.0 | 2         | 6.67%   |
| 2.01-3.0 | 2         | 6.67%   |
| 1.01-2.0 | 1         | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 80.65%  |
| 2      | 3         | 9.68%   |
| 0      | 3         | 9.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 86.67%  |
| Yes       | 4         | 13.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 96.67%  |
| No        | 1         | 3.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 76.67%  |
| Yes       | 7         | 23.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 86.67%  |
| Yes       | 4         | 13.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 18        | 60%     |
| Germany     | 2         | 6.67%   |
| UK          | 1         | 3.33%   |
| Taiwan      | 1         | 3.33%   |
| Sweden      | 1         | 3.33%   |
| Russia      | 1         | 3.33%   |
| New Zealand | 1         | 3.33%   |
| Netherlands | 1         | 3.33%   |
| India       | 1         | 3.33%   |
| Greece      | 1         | 3.33%   |
| Canada      | 1         | 3.33%   |
| Brazil      | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Salem             | 2         | 6.67%   |
| Yegor'yevsk       | 1         | 3.33%   |
| Wellington        | 1         | 3.33%   |
| Waconia           | 1         | 3.33%   |
| Uxbridge          | 1         | 3.33%   |
| Stuttgart         | 1         | 3.33%   |
| Silver Spring     | 1         | 3.33%   |
| Renton            | 1         | 3.33%   |
| Phoenix           | 1         | 3.33%   |
| Philadelphia      | 1         | 3.33%   |
| Pasadena          | 1         | 3.33%   |
| Malmo             | 1         | 3.33%   |
| Longmont          | 1         | 3.33%   |
| Long Beach        | 1         | 3.33%   |
| London            | 1         | 3.33%   |
| Lawrenceville     | 1         | 3.33%   |
| Kottenheim        | 1         | 3.33%   |
| JaraguГЎ do Sul | 1         | 3.33%   |
| Hoboken           | 1         | 3.33%   |
| Fletcher          | 1         | 3.33%   |
| Fair Oaks         | 1         | 3.33%   |
| Douliu            | 1         | 3.33%   |
| Daly City         | 1         | 3.33%   |
| Centreville       | 1         | 3.33%   |
| Bengaluru         | 1         | 3.33%   |
| Atlanta           | 1         | 3.33%   |
| Athens            | 1         | 3.33%   |
| Ashburn           | 1         | 3.33%   |
| Amsterdam         | 1         | 3.33%   |

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
| 101-250    | 9         | 30%     |
| 51-100     | 7         | 23.33%  |
| 21-50      | 6         | 20%     |
| 251-500    | 3         | 10%     |
| 1-20       | 3         | 10%     |
| 501-1000   | 2         | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 29        | 96.67%  |
| 21-50   | 1         | 3.33%   |

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
| Intel                       | 23        | 71.88%  |
| AMD                         | 5         | 15.63%  |
| Silicon Image               | 1         | 3.13%   |
| Micron/Crucial Technology   | 1         | 3.13%   |
| Kingston Technology Company | 1         | 3.13%   |
| JMicron Technology          | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 13.89%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 8.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 5.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 5.56%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 2.78%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 2.78%   |
| Kingston Company NVMe Controller                                                 | 1         | 2.78%   |
| JMicron JMB368 IDE controller                                                    | 1         | 2.78%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2.78%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.78%   |
| Intel Elkhart Lake SATA AHCI                                                     | 1         | 2.78%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1         | 2.78%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1         | 2.78%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1         | 2.78%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1         | 2.78%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 2.78%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 2.78%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 2.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.78%   |
| AMD AMD-8111 IDE                                                                 | 1         | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 77.42%  |
| IDE  | 3         | 9.68%   |
| RAID | 2         | 6.45%   |
| NVMe | 2         | 6.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 80%     |
| AMD    | 5         | 16.67%  |
| ARM    | 1         | 3.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2         | 6.67%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 2         | 6.67%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 6.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 1         | 3.33%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1         | 3.33%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 3.33%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1         | 3.33%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 1         | 3.33%   |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1         | 3.33%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 1         | 3.33%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1         | 3.33%   |
| Intel Celeron N6210 @ 1.20GHz            | 1         | 3.33%   |
| Intel Celeron N5105 @ 2.00GHz            | 1         | 3.33%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 1         | 3.33%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 1         | 3.33%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1         | 3.33%   |
| Intel Celeron CPU 450 @ 2.20GHz          | 1         | 3.33%   |
| Intel Atom CPU D525 @ 1.80GHz            | 1         | 3.33%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 1         | 3.33%   |
| Intel Atom CPU C2758 @ 2.40GHz           | 1         | 3.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1         | 3.33%   |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1         | 3.33%   |
| AMD Opteron Processor 252                | 1         | 3.33%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 1         | 3.33%   |
| AMD GX-412TC SOC                         | 1         | 3.33%   |
| AMD G-T40E Processor                     | 1         | 3.33%   |
| AMD Athlon X4 860K Quad Core Processor   | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Celeron    | 10        | 33.33%  |
| Intel Core i5    | 7         | 23.33%  |
| Intel Atom       | 3         | 10%     |
| Intel Core i7    | 2         | 6.67%   |
| AMD GX           | 2         | 6.67%   |
| Other            | 1         | 3.33%   |
| Intel Core 2 Duo | 1         | 3.33%   |
| ARM Cortex       | 1         | 3.33%   |
| AMD Opteron      | 1         | 3.33%   |
| AMD G            | 1         | 3.33%   |
| AMD Athlon X4    | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 19        | 63.33%  |
| 2       | 7         | 23.33%  |
| Unknown | 3         | 10%     |
| 1       | 1         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 28        | 93.33%  |
| 2       | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 23        | 76.67%  |
| 2       | 4         | 13.33%  |
| Unknown | 3         | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Silvermont  | 6         | 20%     |
| Unknown     | 5         | 16.67%  |
| Haswell     | 3         | 10%     |
| Goldmont    | 3         | 10%     |
| IvyBridge   | 2         | 6.67%   |
| Broadwell   | 2         | 6.67%   |
| TigerLake   | 1         | 3.33%   |
| Steamroller | 1         | 3.33%   |
| Skylake     | 1         | 3.33%   |
| SandyBridge | 1         | 3.33%   |
| Puma        | 1         | 3.33%   |
| Penryn      | 1         | 3.33%   |
| K8 Hammer   | 1         | 3.33%   |
| Bonnell     | 1         | 3.33%   |
| Bobcat      | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 20        | 83.33%  |
| AMD                        | 3         | 12.5%   |
| Matrox Electronics Systems | 1         | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 20.83%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 12.5%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 8.33%   |
| Intel HD Graphics 6000                                                                   | 2         | 8.33%   |
| Intel HD Graphics 500                                                                    | 2         | 8.33%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 4.17%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 4.17%   |
| Intel HD Graphics 530                                                                    | 1         | 4.17%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 1         | 4.17%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 4.17%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1         | 4.17%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1         | 4.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 20        | 66.67%  |
| Other      | 6         | 20%     |
| 1 x AMD    | 3         | 10%     |
| 1 x Matrox | 1         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 24        | 80%     |
| Unknown | 6         | 20%     |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 100%    |

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
| 0     | 30        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 23        | 56.1%   |
| Realtek Semiconductor     | 10        | 24.39%  |
| Qualcomm Atheros          | 3         | 7.32%   |
| Broadcom                  | 2         | 4.88%   |
| Solarflare Communications | 1         | 2.44%   |
| NetXen Incorporated       | 1         | 2.44%   |
| MediaTek                  | 1         | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 10        | 20%     |
| Intel I211 Gigabit Network Connection                                         | 5         | 10%     |
| Intel I210 Gigabit Network Connection                                         | 4         | 8%      |
| Intel Wireless 3165                                                           | 3         | 6%      |
| Intel 82580 Gigabit Network Connection                                        | 3         | 6%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 4%      |
| Intel Ethernet Controller I225-V                                              | 2         | 4%      |
| Intel Ethernet Connection I217-LM                                             | 2         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 4%      |
| Intel 82574L Gigabit Network Connection                                       | 2         | 4%      |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 2%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 2%      |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1         | 2%      |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 2%      |
| Intel Wireless-AC 9260                                                        | 1         | 2%      |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 2%      |
| Intel Ethernet Connection I354                                                | 1         | 2%      |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 2%      |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 2%      |
| Intel 82576 Gigabit Network Connection                                        | 1         | 2%      |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 2%      |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 2%      |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 2%      |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 4         | 57.14%  |
| Qualcomm Atheros | 3         | 42.86%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 3         | 42.86%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 28.57%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 14.29%  |
| Intel Wireless-AC 9260                                                  | 1         | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 20        | 60.61%  |
| Realtek Semiconductor     | 10        | 30.3%   |
| Broadcom                  | 2         | 6.06%   |
| Solarflare Communications | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 10        | 24.39%  |
| Intel I211 Gigabit Network Connection                                         | 5         | 12.2%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 9.76%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 7.32%   |
| Intel Ethernet Controller I225-V                                              | 2         | 4.88%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 4.88%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 4.88%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 2.44%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 2.44%   |
| Intel Ethernet Connection I354                                                | 1         | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 2.44%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 2.44%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 2.44%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 2.44%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 2.44%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 2.44%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 29        | 76.32%  |
| WiFi     | 7         | 18.42%  |
| Modem    | 1         | 2.63%   |
| Unknown  | 1         | 2.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 29        | 100%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 3     | 9         | 30%     |
| 5     | 7         | 23.33%  |
| 2     | 5         | 16.67%  |
| 6     | 4         | 13.33%  |
| 4     | 3         | 10%     |
| 8     | 1         | 3.33%   |
| 0     | 1         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 86.67%  |
| Yes  | 4         | 13.33%  |

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
| Intel  | 18        | 85.71%  |
| AMD    | 3         | 14.29%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 15.38%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 11.54%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 7.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 7.69%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 7.69%   |
| AMD FCH Azalia Controller                                                                         | 2         | 7.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 3.85%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 3.85%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 1         | 3.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 3.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 3.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 3.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 25%     |
| Crucial             | 6         | 21.43%  |
| Samsung Electronics | 4         | 14.29%  |
| Unknown (ABCD)      | 2         | 7.14%   |
| Transcend           | 2         | 7.14%   |
| SK hynix            | 2         | 7.14%   |
| V-Color             | 1         | 3.57%   |
| Unknown (0x1636)    | 1         | 3.57%   |
| Nanya Technology    | 1         | 3.57%   |
| Micron Technology   | 1         | 3.57%   |
| Kingston            | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                           | 2         | 7.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2         | 7.14%   |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s       | 2         | 7.14%   |
| V-Color RAM TN432G32D822 32GB SODIMM DDR4 3200MT/s             | 1         | 3.57%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 1         | 3.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1         | 3.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s                  | 1         | 3.57%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1         | 3.57%   |
| Unknown (0x1636) RAM 5.6.5 4GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s          | 1         | 3.57%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s              | 1         | 3.57%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s                     | 1         | 3.57%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1         | 3.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 3.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1         | 3.57%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s             | 1         | 3.57%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s          | 1         | 3.57%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s         | 1         | 3.57%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB DIMM DDR3 1600MT/s          | 1         | 3.57%   |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s          | 1         | 3.57%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 59.26%  |
| DDR4   | 5         | 18.52%  |
| SDRAM  | 3         | 11.11%  |
| LPDDR4 | 2         | 7.41%   |
| DDR2   | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 18        | 69.23%  |
| SODIMM | 8         | 30.77%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 15        | 57.69%  |
| 16384 | 4         | 15.38%  |
| 2048  | 4         | 15.38%  |
| 8192  | 2         | 7.69%   |
| 32768 | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 11        | 42.31%  |
| 1333    | 4         | 15.38%  |
| 2400    | 3         | 11.54%  |
| 3200    | 2         | 7.69%   |
| 800     | 2         | 7.69%   |
| Unknown | 2         | 7.69%   |
| 2667    | 1         | 3.85%   |
| 2133    | 1         | 3.85%   |

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
| 0     | 13        | 43.33%  |
| 1     | 12        | 40%     |
| 3     | 2         | 6.67%   |
| 2     | 2         | 6.67%   |
| 5     | 1         | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 15        | 60%     |
| Bluetooth                | 5         | 20%     |
| Net/wireless             | 2         | 8%      |
| Card reader              | 2         | 8%      |
| Network                  | 1         | 4%      |

