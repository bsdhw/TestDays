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

Total: 30

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| pfSense 2.4.5       | 10       | 38.46%  |
| pfSense 2.6.0       | 4        | 15.38%  |
| pfSense 2.5.0       | 4        | 15.38%  |
| pfSense 12.3-STABLE | 4        | 15.38%  |
| pfSense 2.4.4       | 2        | 7.69%   |
| pfSense 12.2-STABLE | 2        | 7.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| pfSense | 25       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 24       | 96%     |
| arm   | 1        | 4%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 25       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 25       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 25       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 88%     |
| en_US   | 2        | 8%      |
| pt_BR   | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 15       | 60%     |
| EFI  | 10       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 13       | 52%     |
| Zfs  | 12       | 48%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 18       | 72%     |
| MBR  | 7        | 28%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 3        | 12%     |
| Unknown             | 3        | 12%     |
| Protectli           | 2        | 8%      |
| PC Engines          | 2        | 8%      |
| Lenovo              | 2        | 8%      |
| Intel               | 2        | 8%      |
| Hewlett-Packard     | 2        | 8%      |
| Dell                | 2        | 8%      |
| TYAN Computer       | 1        | 4%      |
| Techvision          | 1        | 4%      |
| Supermicro          | 1        | 4%      |
| Netgate             | 1        | 4%      |
| Itautec             | 1        | 4%      |
| Gigabyte Technology | 1        | 4%      |
| ADI Engineering     | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 4        | 16%     |
| Intel Q3XXG4-P V1.0               | 2        | 8%      |
| Techvision TVI7309X               | 1        | 4%      |
| Supermicro X7SPA-HF               | 1        | 4%      |
| Protectli FW4B                    | 1        | 4%      |
| Protectli FW2B                    | 1        | 4%      |
| PC Engines APU2                   | 1        | 4%      |
| PC Engines APU                    | 1        | 4%      |
| Netgate SG-5100                   | 1        | 4%      |
| Lenovo ThinkCentre M92p 3209D9U   | 1        | 4%      |
| Lenovo ThinkCentre Edge72 3493AZG | 1        | 4%      |
| Itautec Infoway                   | 1        | 4%      |
| HP t620 PLUS Quad Core TC         | 1        | 4%      |
| HP ProDesk 600 G1 SFF             | 1        | 4%      |
| Gigabyte B85M-D3H                 | 1        | 4%      |
| Dell OptiPlex 990                 | 1        | 4%      |
| Dell OptiPlex 7020                | 1        | 4%      |
| ASUS P5Q SE PLUS                  | 1        | 4%      |
| ASUS All Series                   | 1        | 4%      |
| ASUS A88XM-E                      | 1        | 4%      |
| ADI Engineering RCC-VE            | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 4        | 16%     |
| Lenovo ThinkCentre     | 2        | 8%      |
| Intel Q3XXG4-P         | 2        | 8%      |
| Dell OptiPlex          | 2        | 8%      |
| Techvision TVI7309X    | 1        | 4%      |
| Supermicro X7SPA-HF    | 1        | 4%      |
| Protectli FW4B         | 1        | 4%      |
| Protectli FW2B         | 1        | 4%      |
| PC Engines APU2        | 1        | 4%      |
| PC Engines APU         | 1        | 4%      |
| Netgate SG-5100        | 1        | 4%      |
| Itautec Infoway        | 1        | 4%      |
| HP t620                | 1        | 4%      |
| HP ProDesk             | 1        | 4%      |
| Gigabyte B85M-D3H      | 1        | 4%      |
| ASUS P5Q               | 1        | 4%      |
| ASUS All               | 1        | 4%      |
| ASUS A88XM-E           | 1        | 4%      |
| ADI Engineering RCC-VE | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 5        | 20%     |
| 2016    | 3        | 12%     |
| 2015    | 3        | 12%     |
| 2017    | 2        | 8%      |
| 2014    | 2        | 8%      |
| 2009    | 2        | 8%      |
| 2022    | 1        | 4%      |
| 2021    | 1        | 4%      |
| 2019    | 1        | 4%      |
| 2013    | 1        | 4%      |
| 2012    | 1        | 4%      |
| 2010    | 1        | 4%      |
| 2006    | 1        | 4%      |
| Unknown | 1        | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 25       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 88%     |
| Yes  | 3        | 12%     |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 10       | 40%     |
| 4.01-8.0    | 7        | 28%     |
| 16.01-24.0  | 4        | 16%     |
| 2.01-3.0    | 2        | 8%      |
| 32.01-64.0  | 1        | 4%      |
| 64.01-256.0 | 1        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 15       | 60%     |
| 0.51-1.0 | 5        | 20%     |
| 4.01-8.0 | 2        | 8%      |
| 2.01-3.0 | 2        | 8%      |
| 1.01-2.0 | 1        | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 80.77%  |
| 2      | 3        | 11.54%  |
| 0      | 2        | 7.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 88%     |
| Yes       | 3        | 12%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 96%     |
| No        | 1        | 4%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 88%     |
| Yes       | 3        | 12%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 100%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 14       | 56%     |
| UK          | 1        | 4%      |
| Taiwan      | 1        | 4%      |
| Sweden      | 1        | 4%      |
| Russia      | 1        | 4%      |
| New Zealand | 1        | 4%      |
| Netherlands | 1        | 4%      |
| India       | 1        | 4%      |
| Greece      | 1        | 4%      |
| Germany     | 1        | 4%      |
| Canada      | 1        | 4%      |
| Brazil      | 1        | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Salem             | 2        | 8%      |
| Yegor'yevsk       | 1        | 4%      |
| Wellington        | 1        | 4%      |
| Waconia           | 1        | 4%      |
| Uxbridge          | 1        | 4%      |
| Silver Spring     | 1        | 4%      |
| Renton            | 1        | 4%      |
| Pasadena          | 1        | 4%      |
| Malmo             | 1        | 4%      |
| Longmont          | 1        | 4%      |
| Long Beach        | 1        | 4%      |
| London            | 1        | 4%      |
| Lawrenceville     | 1        | 4%      |
| Kottenheim        | 1        | 4%      |
| JaraguГЎ do Sul | 1        | 4%      |
| Hoboken           | 1        | 4%      |
| Fletcher          | 1        | 4%      |
| Douliu            | 1        | 4%      |
| Centreville       | 1        | 4%      |
| Bengaluru         | 1        | 4%      |
| Atlanta           | 1        | 4%      |
| Athens            | 1        | 4%      |
| Ashburn           | 1        | 4%      |
| Amsterdam         | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 6      | 23.08%  |
| Samsung Electronics | 4        | 4      | 15.38%  |
| Seagate             | 3        | 3      | 11.54%  |
| Phison              | 2        | 2      | 7.69%   |
| Intel               | 2        | 2      | 7.69%   |
| Apacer              | 2        | 2      | 7.69%   |
| WDC                 | 1        | 2      | 3.85%   |
| SPCC                | 1        | 1      | 3.85%   |
| SanDisk             | 1        | 1      | 3.85%   |
| Hoodisk             | 1        | 1      | 3.85%   |
| FORESEE             | 1        | 1      | 3.85%   |
| Crucial             | 1        | 1      | 3.85%   |
| China               | 1        | 2      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SUV500MS120G 120GB     | 2        | 7.69%   |
| WDC WD10EFRX-68FYTN0 1TB        | 1        | 3.85%   |
| SPCC Solid State Disk 120GB     | 1        | 3.85%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 3.85%   |
| Seagate ST3160023A 160GB        | 1        | 3.85%   |
| Seagate ST240HM000-1G5152 240GB | 1        | 3.85%   |
| SanDisk SDSSDP064G 64GB         | 1        | 3.85%   |
| Samsung SSD RBX Series 64GB M   | 1        | 3.85%   |
| Samsung SSD 860 EVO 250GB       | 1        | 3.85%   |
| Samsung SSD 850 EVO mSATA 250GB | 1        | 3.85%   |
| Samsung SSD 850 EVO 120GB       | 1        | 3.85%   |
| Phison SATA SSD 32GB            | 1        | 3.85%   |
| Phison SATA SSD 240GB           | 1        | 3.85%   |
| Kingston SUV500MS240G 240GB     | 1        | 3.85%   |
| Kingston SUV500M8120G 120GB     | 1        | 3.85%   |
| Kingston SNVS1000G 1TB          | 1        | 3.85%   |
| Kingston SNS4151S316G 16GB      | 1        | 3.85%   |
| Intel SSDSA2CW080G3 80GB        | 1        | 3.85%   |
| Intel SSDMCEAC030B3 32GB        | 1        | 3.85%   |
| Hoodisk SSD 32GB                | 1        | 3.85%   |
| FORESEE 64GB SSD                | 1        | 3.85%   |
| Crucial CT500P2SSD8 500GB       | 1        | 3.85%   |
| China SATA SSD 256GB            | 1        | 3.85%   |
| Apacer 64GB SATA Flash Drive    | 1        | 3.85%   |
| Apacer 32GB SATA Flash Drive    | 1        | 3.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 2      | 33.33%  |

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
| SSD  | 18       | 22     | 78.26%  |
| HDD  | 3        | 4      | 13.04%  |
| NVMe | 2        | 2      | 8.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 21       | 26     | 91.3%   |
| NVMe | 2        | 2      | 8.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 24     | 95.24%  |
| 0.51-1.0   | 1        | 2      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 51-100     | 7        | 28%     |
| 101-250    | 6        | 24%     |
| 21-50      | 5        | 20%     |
| 1-20       | 3        | 12%     |
| 251-500    | 2        | 8%      |
| 501-1000   | 2        | 8%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 24       | 96%     |
| 21-50   | 1        | 4%      |

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
| Works   | 21       | 26     | 91.3%   |
| Malfunc | 2        | 2      | 8.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 18       | 66.67%  |
| AMD                         | 5        | 18.52%  |
| Silicon Image               | 1        | 3.7%    |
| Micron/Crucial Technology   | 1        | 3.7%    |
| Kingston Technology Company | 1        | 3.7%    |
| JMicron Technology          | 1        | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 12.9%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3        | 9.68%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3        | 9.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2        | 6.45%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1        | 3.23%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 3.23%   |
| JMicron JMB368 IDE controller                                                    | 1        | 3.23%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1        | 3.23%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 3.23%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1        | 3.23%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 3.23%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1        | 3.23%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1        | 3.23%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 3.23%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 3.23%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 3.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1        | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1        | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1        | 3.23%   |
| AMD AMD-8111 IDE                                                                 | 1        | 3.23%   |
| Unknown                                                                          | 1        | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 73.08%  |
| IDE  | 3        | 11.54%  |
| RAID | 2        | 7.69%   |
| NVMe | 2        | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 76%     |
| AMD    | 5        | 20%     |
| ARM    | 1        | 4%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2        | 8%      |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2        | 8%      |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1        | 4%      |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 4%      |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1        | 4%      |
| Intel Core i5-3570 CPU @ 3.40GHz         | 1        | 4%      |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1        | 4%      |
| Intel Core i5-2400 CPU @ 3.10GH          | 1        | 4%      |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1        | 4%      |
| Intel Celeron N5105 @ 2.00GHz            | 1        | 4%      |
| Intel Celeron CPU N3150 @ 1.60GHz        | 1        | 4%      |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1        | 4%      |
| Intel Celeron CPU 450 @ 2.20GHz          | 1        | 4%      |
| Intel Atom CPU D525 @ 1.80GHz            | 1        | 4%      |
| Intel Atom CPU C3558 @ 2.20GHz           | 1        | 4%      |
| Intel Atom CPU C2758 @ 2.40GHz           | 1        | 4%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1        | 4%      |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1        | 4%      |
| AMD Opteron Processor 252                | 1        | 4%      |
| AMD GX-420CA SOC with Radeon HD Graphics | 1        | 4%      |
| AMD GX-412TC SOC                         | 1        | 4%      |
| AMD G-T40E Processor                     | 1        | 4%      |
| AMD Athlon X4 860K Quad Core Processor   | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 6        | 24%     |
| Intel Celeron    | 6        | 24%     |
| Intel Atom       | 3        | 12%     |
| Intel Core i7    | 2        | 8%      |
| AMD GX           | 2        | 8%      |
| Other            | 1        | 4%      |
| Intel Core 2 Duo | 1        | 4%      |
| ARM Cortex       | 1        | 4%      |
| AMD Opteron      | 1        | 4%      |
| AMD G            | 1        | 4%      |
| AMD Athlon X4    | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 15       | 60%     |
| 2       | 6        | 24%     |
| Unknown | 3        | 12%     |
| 1       | 1        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 23       | 92%     |
| 2       | 1        | 4%      |
| Unknown | 1        | 4%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 18       | 72%     |
| 2       | 4        | 16%     |
| Unknown | 3        | 12%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Silvermont  | 5        | 20%     |
| Unknown     | 4        | 16%     |
| Haswell     | 3        | 12%     |
| IvyBridge   | 2        | 8%      |
| Broadwell   | 2        | 8%      |
| TigerLake   | 1        | 4%      |
| Steamroller | 1        | 4%      |
| SandyBridge | 1        | 4%      |
| Puma        | 1        | 4%      |
| Penryn      | 1        | 4%      |
| K8 Hammer   | 1        | 4%      |
| Goldmont    | 1        | 4%      |
| Bonnell     | 1        | 4%      |
| Bobcat      | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 15       | 78.95%  |
| AMD                        | 3        | 15.79%  |
| Matrox Electronics Systems | 1        | 5.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 21.05%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 15.79%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 10.53%  |
| Intel HD Graphics 6000                                                                   | 2        | 10.53%  |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 5.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 5.26%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 5.26%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 5.26%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1        | 5.26%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1        | 5.26%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 15       | 60%     |
| Other      | 6        | 24%     |
| 1 x AMD    | 3        | 12%     |
| 1 x Matrox | 1        | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 19       | 76%     |
| Unknown | 6        | 24%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 100%    |

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
| 0     | 25       | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 18       | 54.55%  |
| Realtek Semiconductor     | 7        | 21.21%  |
| Qualcomm Atheros          | 3        | 9.09%   |
| Broadcom                  | 2        | 6.06%   |
| Solarflare Communications | 1        | 3.03%   |
| NetXen Incorporated       | 1        | 3.03%   |
| MediaTek                  | 1        | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7        | 17.5%   |
| Intel I211 Gigabit Network Connection                                         | 4        | 10%     |
| Intel I210 Gigabit Network Connection                                         | 4        | 10%     |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2        | 5%      |
| Intel Ethernet Controller I225-V                                              | 2        | 5%      |
| Intel Ethernet Connection I217-LM                                             | 2        | 5%      |
| Intel 82580 Gigabit Network Connection                                        | 2        | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 5%      |
| Intel 82574L Gigabit Network Connection                                       | 2        | 5%      |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 2.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 2.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1        | 2.5%    |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1        | 2.5%    |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 2.5%    |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 2.5%    |
| Intel Ethernet Connection I354                                                | 1        | 2.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.5%    |
| Intel 82576 Gigabit Network Connection                                        | 1        | 2.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 2.5%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 2.5%    |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Qualcomm Atheros | 3        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2        | 66.67%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 18       | 64.29%  |
| Realtek Semiconductor     | 7        | 25%     |
| Broadcom                  | 2        | 7.14%   |
| Solarflare Communications | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7        | 20%     |
| Intel I211 Gigabit Network Connection                                         | 4        | 11.43%  |
| Intel I210 Gigabit Network Connection                                         | 4        | 11.43%  |
| Intel Ethernet Controller I225-V                                              | 2        | 5.71%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 5.71%   |
| Intel 82580 Gigabit Network Connection                                        | 2        | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 5.71%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 5.71%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 2.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 2.86%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 2.86%   |
| Intel Ethernet Connection I354                                                | 1        | 2.86%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.86%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 2.86%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.86%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 2.86%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 2.86%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 82.76%  |
| WiFi     | 3        | 10.34%  |
| Modem    | 1        | 3.45%   |
| Unknown  | 1        | 3.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 5     | 6        | 24%     |
| 3     | 5        | 20%     |
| 2     | 5        | 20%     |
| 6     | 4        | 16%     |
| 4     | 3        | 12%     |
| 8     | 1        | 4%      |
| 0     | 1        | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 88%     |
| Yes  | 3        | 12%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

Zero info for selected period =(

Bluetooth Model
---------------

Controller models

Zero info for selected period =(

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 81.25%  |
| AMD    | 3        | 18.75%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 14.29%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 14.29%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 9.52%   |
| Intel Broadwell-U Audio Controller                                                                | 2        | 9.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 9.52%   |
| AMD FCH Azalia Controller                                                                         | 2        | 9.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1        | 4.76%   |
| Intel Jasper Lake HD Audio                                                                        | 1        | 4.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 4.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 4.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 4.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 30.43%  |
| Crucial             | 5        | 21.74%  |
| Samsung Electronics | 4        | 17.39%  |
| Transcend           | 2        | 8.7%    |
| V-Color             | 1        | 4.35%   |
| SK hynix            | 1        | 4.35%   |
| Nanya Technology    | 1        | 4.35%   |
| Micron Technology   | 1        | 4.35%   |
| Kingston            | 1        | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2        | 8.7%    |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s | 2        | 8.7%    |
| V-Color RAM TN432G32D822 32GB SODIMM DDR4 3200MT/s       | 1        | 4.35%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s      | 1        | 4.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1        | 4.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 4.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s            | 1        | 4.35%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 4.35%   |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s    | 1        | 4.35%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s        | 1        | 4.35%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 4.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 4.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 4.35%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 4.35%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 4.35%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s       | 1        | 4.35%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 4.35%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 4.35%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s   | 1        | 4.35%   |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s    | 1        | 4.35%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s    | 1        | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 15       | 71.43%  |
| DDR4  | 3        | 14.29%  |
| SDRAM | 2        | 9.52%   |
| DDR2  | 1        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 14       | 66.67%  |
| SODIMM | 7        | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 12       | 57.14%  |
| 2048  | 4        | 19.05%  |
| 16384 | 2        | 9.52%   |
| 8192  | 2        | 9.52%   |
| 32768 | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 47.62%  |
| 1333    | 4        | 19.05%  |
| 3200    | 2        | 9.52%   |
| 800     | 2        | 9.52%   |
| Unknown | 2        | 9.52%   |
| 2400    | 1        | 4.76%   |

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
| 0     | 13       | 52%     |
| 1     | 11       | 44%     |
| 2     | 1        | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 11       | 91.67%  |
| Network                  | 1        | 8.33%   |

